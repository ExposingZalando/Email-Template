# Zalando Email Protest Tool

A simple HTML/JavaScript tool to help supporters send pre-formatted protest emails to Zalando management with one click. Automatically inserts the current date and preserves email formatting.

## Features

- 📅 **Auto-date insertion**: Replaces `[date of sending]` with today's date
- ✊ **Pre-filled protest content**: Maintains perfect formatting (paragraphs, lists, indentation)
- 📧 **Multi-recipient CC**: Includes all specified Zalando contacts
- 📱 **Mobile-friendly**: Works on all devices

## How to Use

### Option A: Host Online (Recommended)
1. **Deploy to GitHub Pages**:
   - Create a new GitHub repository
   - Upload `zalando-email.html`
   - Enable GitHub Pages in Settings
   - Share the link (e.g., `https://[username].github.io/repo/zalando-email.html`)

2. **Deploy to Netlify**:
   - Drag/drop the HTML file to [Netlify Drop](https://app.netlify.com/drop)
   - Share the auto-generated link

### Option B: Use Locally
1. Download `zalando-email.html`
2. Open in any web browser
3. Click "Open Email Draft" button

## Customization
Edit these elements in the HTML file:
- **Recipients**: Update the `recipients` and `cc` variables in the JavaScript
- **Email Content**: Modify the text inside the `<textarea>`
- **Styling**: Adjust the CSS in the `<style>` section

## Technical Details
- **Date Format**: Uses browser's locale (e.g. "12 July 2024" for en-GB)
- **Encoding**: Automatically handles URI encoding for line breaks (`%0A`) and spaces (`%20`)
- **Compatibility**: Works with all modern browsers and email clients

## Example Instagram Post
```plaintext
📢 TAKE ACTION: Demand @Zalando stop repressing Palestine solidarity! 

One-click email tool → bit.ly/zalando-protest 

#BoycottZalando #FreePalestine
