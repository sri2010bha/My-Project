<img width="1943" height="1093" alt="image" src="https://github.com/user-attachments/assets/cc2ff955-17c2-48c7-81c8-479a0f061850" />

# DevPortfolio Template

A modern, minimalist portfolio template built with Astro and Tailwind CSS. Perfect for developers looking to showcase their skills, experience, and projects in a clean, professional way.

This was completely rebuilt from the ground up from V1. This template was built to be entirely ready to go with a quick config edit (see below) but also provides the ability to easily extend in whatever way you want.

This template also comes with `CLAUDE.md` and `.cursor/rules` files for easy integration with your existing AI workflows.

> **📬 Connect & Share!**  
> For questions and updates, feel free to reach out on [**X (Twitter)**](https://x.com/rfitzio).  
> If you've built and published your personal site with this template, I'd love to see it! Send me a DM 🚀

## Preview

To view a live preview of the site, [click here](https://ryanfitzgerald.github.io/devportfolio/).

## Built With

- **[Astro](https://astro.build/)** - Static site generator for modern web apps
- **[Tailwind CSS v4](https://tailwindcss.com/)** - Utility-first CSS framework
- **[Tabler Icons](https://tabler.io/icons)** - Free and open source icons
- **TypeScript** - For type-safe configuration

## Updating the Template

### Configuration

The template is designed to be easily customizable through the `src/config.ts` file. This single file controls:

- **Personal Information**: Name, title, description
- **Accent Color**: Primary color theme (changing this will change the accent color site wide)
- **Social Links**: Email, LinkedIn, Twitter, GitHub (all optional)
- **About Section**: Personal bio/description
- **Skills**: List of technical skills
- **Projects**: Project showcase with descriptions and links
- **Experience**: Work history with bullet points
- **Education**: Educational background and achievements

If skills, projects, experience, or education are removed from the config, those sections will be hidden entirely.

### Example structures

Here's what the config data structure looks like for each section:

#### Basic Information
```typescript
name: Sri B
title: Personal Web Developer
description: Website ABOUT ME
accentColor: "#1d4ed8", // Hex color for theme
```

#### Social Links (all optional)
```typescript
social: {
  email: "sri2010bha@gmail.com",
  linkedin: "https://linkedin.com/in/yourprofile",
  twitter: "https://twitter.com/yourprofile", 
  github: "https://github.com/yourusername",
}
```

#### About Section
```typescript
aboutMe: Hi, I am Sri. I’m a junior at Metea Valley High School, and I am really into STEM and computer science. I have learned a bit of coding inside and outside of school by myself. I also have attended and gone to programs to learn more about physics in Fermilab.
```

#### Skills
```typescript
skills:
Technical: Learned basic Python and Javascript
Language: Fluent in English and Spanish (learned in school)
Interests: Learning about new cars, Playing Basketball, Coding in free time

```

#### Projects
```typescript
projects: [
  {
name: Personal Portfolio Website
 What it is: A personal website and digital portfolio to showcase my achievements
 What you did: Structured the website pages, customized user interface, and ensured responsive design for mobile and all devices
 Technologies used: HTML, CSS, Git, GitHub pages
  }
]
```

#### Experience
```typescript
experience: [
  {
    company: "Company Name",
    title: "Your Job Title",
    dateRange: "Jan 2022 - Present",
    bullets: [
      "Led development of microservices architecture serving 1M+ users",
      "Reduced API response times by 40% through optimization",
      "Mentored team of 5 junior developers",
    ],
  }
]
```

#### Education
```typescript
education: [
  {
    school: Metea Valley High School
    year: Junior
    dateRange: 2024 - 2028
    achievements: [
      Key Club	    City, State
Member	  Sep 2024 – May 2026
Collaborated with an organization that is student led and helped plan community service
Developed leadership skills and responsibility through volunteer work

TedEd Club	    City, State
Participant	  Sep 2025 – May 2026
Developed strong public speaking skills
Collaborated with peers to discuss ideas and give feedback


    ]
  }
]
```

### Icons

The template uses [Tabler Icons](https://tabler.io/icons) for all icons. If you wish to add more icons and have it look consistent with what's already there, you can browse through their extensive icon library.

## Project Structure

```
devportfolio/
├── public/
│   └── favicon.svg          # Site favicon
├── src/
│   ├── components/          # Astro components
│   │   ├── About.astro      # About section
│   │   ├── Education.astro  # Education section
│   │   ├── Experience.astro # Work experience section
│   │   ├── Footer.astro     # Site footer
│   │   ├── Header.astro     # Navigation header
│   │   ├── Hero.astro       # Hero/intro section
│   │   └── Projects.astro   # Projects showcase
│   ├── pages/
│   │   └── index.astro      # Main page layout
│   ├── styles/
│   │   └── global.css       # Global styles
│   └── config.ts            # Site configuration
├── astro.config.mjs         # Astro configuration
├── package.json             # Project dependencies
├── tailwind.config.js       # Tailwind configuration
└── tsconfig.json            # TypeScript configuration
```

## Local Development

If you'd like to run it locally:

```
git clone https://github.com/RyanFitzgerald/devportfolio.git
cd devportfolio
npm install
```

After that, start up the Astro dev server with:

```
npm run dev
```

## Deployment

The template can be deployed to any static hosting service easily (and in most cases, completely free). Here are some options:

- To deploy with Netlify, [click here](https://docs.astro.build/en/guides/deploy/netlify/).
- To deploy with Vercel, [click here](https://docs.astro.build/en/guides/deploy/vercel/).
- To deploy with GitHub Pages, [click here](https://docs.astro.build/en/guides/deploy/github/).
- To deploy with Cloudflare Pages, [click here](https://docs.astro.build/en/guides/deploy/cloudflare/).
- To deploy with Render, [click here](https://docs.astro.build/en/guides/deploy/render/).

Want to deploy somewhere else? Find more guides [here](https://docs.astro.build/en/guides/deploy/).

## Changelog

To view the changelog, see CHANGELOG.md.

## License

This project is fully and completely MIT. See LICENSE.md.

## Questions?

Feel free to reach out on [X (Twitter)](https://x.com/rfitzio) if you have any questions or need help.
