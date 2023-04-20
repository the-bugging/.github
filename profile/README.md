# the-bugging

TheBugging is a complete SaaS platform that offers error logging, helping identifying and fixing production bugs in real-world web applications. We also strongly believe in open-source and giving back to the community that has supported us.

## Table of Contents

- [Requirements](#requirements)
- [Installation](#installation)
- [Open-source](#open-source)

---

## Requirements

- Grab your _projectKey_ at [www.thebugging.com](https://www.thebugging.com).

> Important: This is only for web projects and thus only runs on the client-side.

---

## Installation

- First, add the dependency to your project

```bash
  npm install the-bugging
```

- Or alternatively, with yarn:

```bash
  yarn add the-bugging
```

- With a valid _projectKey_, simply start at the very top of your web project like so:

```tsx
import TheBugging from "the-bugging";

TheBugging.init({ projectKey: "VALID-PROJECT-KEY" });
```

For more detailed installation instructions for specific frameworks, please see our [documentation](https://docs.thebugging.com).

## Open-source

As a part of our commitment to the open-source community, we have made available these packages:

- [istanbul-badges-readme](https://github.com/the-bugging/istanbul-badges-readme): A GitHub action to add Istanbul coverage badges to your README.
- [react-use-hotjar](https://github.com/the-bugging/react-use-hotjar): A React Hook to add Hotjar tracking to your web application.
- [react-use-downloader](https://github.com/the-bugging/react-use-downloader): A React Hook to download files from an URL.
- [react-use-scripts](https://github.com/the-bugging/react-use-scripts): A React Hook to dynamically load scripts.
- [react-use-presentation](https://github.com/the-bugging/react-use-presentation): A React Hook to create presentations easily.

---

We hope our packages can help you in your development process. If you have any questions or feedback, please don't hesitate to [reach out to us](https://www.thebugging.com/contact)
