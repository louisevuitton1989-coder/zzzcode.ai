# Security Policy

## Supported Versions

Use this section to tell people about which versions of your project are
currently being supported with security updates.

| Version | Supported          |
| ------- | ------------------ |
| 5.1.x   | :white_check_mark: |
| 5.0.x   | :x:                |
| 4.0.x   | :white_check_mark: |
| < 4.0   | :x:                |

## Reporting a Vulnerability

Use this section to tell people how to report a vulnerability.

Tell them where to go, how often they can expect to get an update on a
reported vulnerability, what to expect if the vulnerability is accepted or
declined, etc.
gh workflow run <workflow-name> --repo zzzprojects/zzzcode.ai
// Method to add a bot to the server
public function addBot(bot: Bot) {
    try {
        // Check if the bot is null
        if (bot == null) {
            throw new Exception("Cannot add a null bot.");
        }
        
        // Check if the bot is already connected
        if (this.connectedBots.contains(bot)) {
            throw new Exception("Bot is already connected.");
        }
        
        // Add the bot to the list of connected bots
        this.connectedBots.append(bot);
        print("Bot added: " + bot.getName());
        
    } catch (Exception e) {
        // Handle the exception by printing an error message
        print("Error adding bot: " + e.message);
    }
}
