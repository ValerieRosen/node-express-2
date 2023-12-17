Bug #1: In routes>auth.js file let was changed to const and await was added.

Bug #2: In users.js code was added because all fields should not be returned.

Bug #3: In users.js requireAdmin allowed only staff but anyone should have access.

Bug #4: In users.js params allowed you to enter username, admin.

Bug #5: In users.js router.delete doesn't await.

Tricky Bug #6: Auth function in middleware is decode not verify
