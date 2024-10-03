# Secret Message Encoder and Decoder

This is a web-based application that allows users to encode a message into a Base64 format and share it through a URL. The recipient can decode and view the message simply by visiting the generated link.

## How It Works:

1. **Message Encoding**:
   - The user enters a message in the input form.
   - The message is Base64 encoded using `btoa()` and appended as a hash (`#`) in the URL.
   - A sharable link is generated for the user.

2. **Message Decoding**:
   - When someone visits the link, the Base64 encoded message is automatically decoded using `atob()` and displayed on the page.

## Usage Instructions:

1. Clone or download this project.
2. Open the `index.html` file in your browser.
3. Enter a secret message in the form and click **Submit**.
4. Copy the generated link and share it with others. When someone opens the link, the message will be decoded and displayed.



