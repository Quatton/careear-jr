# Careear

## Motivation

### Why Careear?

- Guided journaling helps when you're stuck or don't know where to start with free-form writing
- Thoughtfully crafted prompts ensure meaningful self-reflection
- Centralized platform makes it easy to discover and share journal prompts
- Community-driven development allows for translations and customizations
- Fully open-source project, from technology to content

### Why Not Use Notion Templates?

- Notion templates are scattered across different platforms
- Careear provides a centralized directory for journaling templates
- Simple "Copy as Markdown" functionality
- Future plans may include direct Notion workspace integration

## How to Contribute

### Pull Requests

- Currently, contributions are managed through GitHub pull requests
- While requiring a GitHub account and Git knowledge creates a barrier, it ensures quality control

### Content Structure

```
content/
├── template/
│   ├── [feeling]/
│   │   ├── [sub-category]/
│   │   │   ├── [language].md
```

All content is written in Markdown without strict formatting requirements.

#### Content Contribution Options:

1. Improve existing templates
2. Add translations for templates
3. Create new templates
   - Fork existing templates to add variations
   - Place variations in appropriate sub-category folders

### Technical Contributions

#### Ways to Help:
1. Submit pull requests for code changes
2. Create issues for feature requests or bug reports

#### Technical Stack:
- Built with Nuxt.js and Nuxt UI
- Additional Nuxt modules (see `nuxt.config.ts`)
- Hosted on Vercel

#### Future Plans:
- Authentication system
- CMS/Database integration
- Automatic translation features
- Premium functionality