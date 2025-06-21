# System design
If you’re not sure what “system design” means, start here.

1. Talk me through a full stack implemention of an autocomplete widget. A user can type text into it, and get back results from a server.

    - How would you design a frontend to support the following features:
        - Fetch data from a backend API
        - Render results as a tree (items can have parents/children - it’s not just a flat list)
        - Support for checkbox, radio button, icon, and regular list items - items come in many forms
    - What does the component’s API look like?
    - What does the backend API look like?
    - What perf considerations are there for complete-as-you-type behavior? Are there any edge cases (for example, if the user types fast and the network is slow)?
    - How would you design the network stack and backend in support of fast performance: how do your client/server communicate? How is your data stored on the backend? How do these approaches scale to lots of data and lots of clients?

2. Talk me through a full stack Twitter implementation (shamelessly stolen from my friend Michael Vu).

    - How do you fetch and render tweets?
    - How do you update tweets as new ones come in? How do you know when new ones came in?
    - How do you search tweets? How do you search by author? Talk me through your database, backend, and API designs.
