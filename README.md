# Annika Merris' Resume

## Why is this?

I need to (as of the day I write this) find a UK-based job that is willing to
sponsor a worker visa. My partner has found a job in Edinburgh and the
government has become hostile towards so many folks in the U.S.

## What is this?

Just a little resume site made with Hugo and Cloudflare workers. I also need to
convert this to a more typical "printable" resume.

### Usage bits

For development the site can be live previewed by running: `hugo serve`.  
If running the command from a different machine than the preview will be
accessed on, then you need to run: `hugo serve --bind 0.0.0.0`. 
This will cause the serve command to listen on all devices, instead of only
being available locally. If you want drafts to also be included in the site,
add the flag, `--buildDrafts`. Then it will also include content marked as not
ready for production for the serve command. (Drafts are not compiled into the
final release builds.)
