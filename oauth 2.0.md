Problem

Resource owner had to share her creds with any applications that need access to her resource - for example, Alice needs to share her password of her photo-sharing service to a photo printing service to get her photos printed.

Solution
Instead, she authenticates directly with a server trusted by the photo-sharing service (called authorization server), which issues the printing service delegation specific credentials (called access token)