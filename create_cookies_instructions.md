
# Handling Age-Restricted Videos

To download age-restricted YouTube videos, you need to provide YouTube cookies from a logged-in session.

## Steps to enable age-restricted video downloads:

1. **Export YouTube cookies:**
   - Install a browser extension like "Get cookies.txt LOCALLY" for Chrome/Firefox
   - Go to YouTube.com and make sure you're logged in
   - Use the extension to export cookies as `youtube_cookies.txt`

2. **Upload cookies file:**
   - Place the `youtube_cookies.txt` file in the `uploads/` directory
   - The system will automatically detect and use it for age-restricted videos

3. **Alternative method (if cookies don't work):**
   - Some age-restricted videos may still fail due to YouTube's restrictions
   - In such cases, the video owner needs to make the content publicly accessible

## Security Note:
- Never share your cookies file as it contains your login session
- Regenerate cookies periodically for security
- The cookies file is automatically used when present and ignored when missing

## File Location:
Place your cookies file at: `uploads/youtube_cookies.txt`
