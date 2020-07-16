### Installation:
1. The color scheme is automated, is choosed by user system color.
2. If your app has user preference of color scheme, just toggle the bootstrap files
3. Add this lines on \<head\>:
		<link rel="stylesheet" href="/path/to/bootstrap.css">
		<link rel="stylesheet" href="/path/to/bootstrap.dark.css" media="(prefers-color-scheme: dark)">

### Important:
#### Changing the media attribute.
- media="(prefers-color-scheme: dark)"
	- User system is using light theme, your app will be displayed in bootstrap colors
	- User system is using dark theme, your app will be displayed in bootstrap-dark colors
- media="(prefers-color-scheme: light)"
	- User system is using light theme, your app will be displayed in bootstrap-dark colors
	- User system is using dark theme, your app will be displayed in bootstrap colors

<!-- 3. Changing the light/dark media attribute will work differently for each user, not necessarily will be dark/light. This depend of system color scheme of each user.
4. Use the media attribute to choose your color scheme.
5. *Everything* is going according to **plan**. -->