# Bootstrap-dark

### Installation:
1. The color scheme is automated, is choosed by user system color scheme.
2. If your app has user preference of color scheme, just toggle the bootstrap files.
3. Add this lines on \<head\>:
		<link rel="stylesheet" href="/path/to/bootstrap.css">
		<link rel="stylesheet" href="/path/to/bootstrap.dark.css" media="(prefers-color-scheme: dark)">

### Important:
#### Changing the media attribute.
- media="(prefers-color-scheme: dark)"
	- User system is using light theme, your app will be displayed in bootstrap colors.
	- User system is using dark theme, your app will be displayed in bootstrap-dark colors.
- media="(prefers-color-scheme: light)"
	- User system is using light theme, your app will be displayed in bootstrap-dark colors.
	- User system is using dark theme, your app will be displayed in bootstrap colors.

### Bugs | Suggestions
- If you found a bug, please report to me so that I can fix.
- Suggestions are welcome.

## Under development