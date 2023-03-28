Simple Python code for keylogger.

Noticed Limitation:
- Does not capture UAC prompt keystores.
	-- What happens here is that when the UAC prompt is displayed the desktop is switched to the Secure Desktop where a screenshot of the Default desktop is taken dimmed and shown on the background and then the UAC prompt is created there isolated. Since this desktop is running on the same session as the user maybe it's still possible to capture it without having to elevate your program privileges.
