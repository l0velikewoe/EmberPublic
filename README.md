# Ember App Configuration

This repository contains the public configuration files for the Ember app. The main application code is kept private for security reasons.

## 📁 Configuration Files

This repository contains the following configuration files:

- **Personas**: AI personality configurations
- **Models**: Available AI models and their settings
- **Voices**: Text-to-speech voice configurations
- **Prompts**: System prompts and conversation templates
- **Journey Settings**: Therapy session journey configurations
- **Psychology Insights**: Therapeutic insight configurations

## 🔄 Updates

These configuration files are automatically synced from the private repository. To update them:

1. Make changes in the private repository
2. Run the sync script: `./scripts/sync_public_config.sh`
3. Changes will be pushed to this public repository

## 📋 Usage

The Ember app pulls these configurations from this public repository to:
- Load available personas and their settings
- Configure AI models and voices
- Apply system prompts and conversation templates
- Set up therapy session journeys
- Display psychology insights

## 🔒 Security

- **Public**: Configuration files (this repository)
- **Private**: Application code, API keys, and sensitive data

## 📞 Support

For issues or questions about the Ember app, please contact the development team.

---

*Last updated: $(date)* 