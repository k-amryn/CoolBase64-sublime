# CoolBase64-sublime
 Sublime Text 3 plugin with a few functions for encoding to and from Base64 

1. Encode selected text to Base64
2. Decode selected Base64 to normal text
3. Copy the current file as Base64. Works with any filetype
	because it processes the file itself instead of the visible
	text.
4. Copy the current file as a Base64 web URL for embedding within 
	HTML or CSS (coolest function). Almost the same as the previous
	function, but it detects the filetype and prepends 
	"data:image/jpg;base64," or "data:audio/ogg;base64," or
	whatever filetype to the beginning of the Base64 encoding. Works
	with any filetype but designed for browser-playable media files.

- `alt+shift+u`: Copy current file as a Base64 web URL
- `alt+shift+e` on selected text: Encode to Base64 in place
- `alt+shift+e` without selected text: Copy whole file as Base64 text
- `alt+shift+d` on selected Base64 text: Decode from Base64

Right click on tab: 
1. Copy file as Base64
2. Copy file as Base64 web URL