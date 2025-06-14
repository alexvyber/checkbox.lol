# Checkboxes

## What?

Do the app that works with as many checkboxes, as possible

## Self-imposed rules and restrictions

1. Only node.js (no bun or deno)
2. Only allowed languages: js, ts, c and c++
3. If backend framework used, only fastify allowed
4. If frontend framewok used, only react allowed
5. Database - only postgres
6. InMemory cache - only DragonflyDB allowed
7. FrontEnd state lib - only legend state allowed
8. CSS - only stylex allowed
9. Most or all the work should be done by node
10. SQL in broswer - only PGLite
11. Maximum hosting budget is 1000$ per month.
12. It should scale up to 50 trillion checkboxes on one server node ( up to 8 tb disk space ).
13. It has to have special view, in which 1 pixel on the screen is 1 checkbox. User can press down, hold the cursor, move around the screen, and checkboxes under the cursor should flip.
14. The whole app should be tested with k6 during the whole dev cycle
15. App should be well-protected against bots and scripts
16. App should be scalable horizontally basically up to infinite number of checkboxes
17. Custon protocol, which sends the smallest payload: addresses to flip or entire block
18. Use as much effect-ts as possible.
