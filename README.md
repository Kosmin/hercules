# Hercules
Helps make strong parameters stronger, by letting you quickly specify which params to permit, and completely ignore invalid params for which there is no error handling.

Another source of problems is when you want to permit different params depending on routes. However, when defining something like `user_params` this method can then be accessed from everywhere, which can then cause coupling with other service methods, etc.
