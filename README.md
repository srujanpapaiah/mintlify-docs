# Intra Documentation

Official documentation for [Intra](https://tryintra.app) - the open agent registry and orchestration platform built on Google's A2A Protocol.

## 🚀 About Intra

Intra is an **open agent registry and orchestration platform** that provides enterprise-grade infrastructure for AI agent discovery, communication, and secure payments. We enable seamless interoperability across different platforms and frameworks by building on open standards like A2A and AP2.

**Website:** [tryintra.app](https://tryintra.app)  
**Documentation:** [docs.tryintra.app](https://docs.tryintra.app)  
**Version:** 0.0.1

## 📚 Documentation Structure

This repository contains the complete documentation for Intra, built with [Mintlify](https://mintlify.com).

### Content Organization

```
├── index.mdx                      # Homepage and introduction
├── quickstart.mdx                 # Quick start guide
├── core-technology/
│   ├── a2a-protocol.mdx          # Agent-to-Agent Protocol
│   └── ap2-protocol.mdx          # Agent Payments Protocol
├── platform/
│   ├── features.mdx              # Platform features
│   └── architecture.mdx          # System architecture
└── api-reference/
    ├── introduction.mdx          # API overview
    └── endpoint/                 # API endpoints
        ├── create.mdx
        ├── get.mdx
        ├── delete.mdx
        └── webhook.mdx
```

## 🛠️ Development

### Prerequisites

- Node.js 18+ and npm/yarn
- [Mintlify CLI](https://www.npmjs.com/package/mintlify)

### Local Development

Install Mintlify:

```bash
npm i -g mintlify
```

Run the documentation locally:

```bash
mintlify dev
```

The documentation will be available at `http://localhost:3000`.

### Making Changes

1. Edit the `.mdx` files in this repository
2. Preview changes locally with `mintlify dev`
3. Commit and push your changes
4. Changes will automatically deploy to production

## 📖 Key Documentation Pages

### Getting Started
- **[Introduction](index.mdx)** - Overview of Intra and its mission
- **[Quick Start](quickstart.mdx)** - Get your first agent running in minutes

### Core Concepts
- **[A2A Protocol](core-technology/a2a-protocol.mdx)** - Complete guide including use cases, pricing, and roadmap
- **[AP2 Protocol](core-technology/ap2-protocol.mdx)** - Understand secure agent payments
- **[Platform Features](platform/features.mdx)** - Explore Intra's capabilities
- **[Architecture](platform/architecture.mdx)** - System design and components
- **[API Reference](api-reference/introduction.mdx)** - Complete API documentation

## 🎨 Design System

The documentation uses Intra's brand colors:

```json
{
  "primary": "#4F46E5",   // Indigo 600
  "light": "#6366F1",     // Indigo 500
  "dark": "#4338CA"       // Indigo 700
}
```

## 🤝 Contributing

We welcome contributions to improve our documentation!

### How to Contribute

1. Fork this repository
2. Create a feature branch (`git checkout -b docs/improve-quickstart`)
3. Make your changes
4. Test locally with `mintlify dev`
5. Commit your changes (`git commit -m 'Improve quickstart guide'`)
6. Push to the branch (`git push origin docs/improve-quickstart`)
7. Open a Pull Request

### Writing Guidelines

- Use clear, concise language
- Include code examples where appropriate
- Add images/diagrams to explain complex concepts
- Use Mintlify components (Card, Accordion, Tabs, etc.)
- Follow the existing structure and style

## 📝 Mintlify Features Used

This documentation leverages several Mintlify features:

- **Card Groups** - For feature highlights and navigation
- **Tabs** - For multi-language code examples
- **Accordions** - For collapsible content sections
- **Steps** - For sequential instructions
- **Code Blocks** - Syntax-highlighted code examples
- **Info/Warning Boxes** - Callouts for important information
- **API Reference** - Auto-generated API documentation

## 🔗 Related Resources

- **Main Website:** [tryintra.app](https://tryintra.app)
- **API:** [api.tryintra.app](https://api.tryintra.app)
- **Dashboard:** [tryintra.app/dashboard](https://tryintra.app/dashboard)
- **Status Page:** [status.tryintra.app](https://status.tryintra.app)
- **Community:** [community.tryintra.app](https://community.tryintra.app)

## 📄 License

This documentation is part of the Intra project and is available under the [MIT License](LICENSE).

## 💬 Support

Need help with the documentation?

- **Email:** [support@tryintra.app](mailto:support@tryintra.app)
- **Community Forum:** [community.tryintra.app](https://community.tryintra.app)
- **GitHub Issues:** [Report an issue](https://github.com/intra-app/mintlify-docs/issues)

---

**Last Updated:** September 30, 2025  
**Built with** [Mintlify](https://mintlify.com) ❤️