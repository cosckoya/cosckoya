# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a GitHub profile repository. The README.md file in this repository is automatically displayed on the GitHub profile page at https://github.com/cosckoya.

## Repository Structure

```
cosckoya/
├── README.md           # Profile page content (displayed on GitHub profile)
└── img/               # Images referenced in README.md
```

## Working with README.md

The README.md serves as the public-facing GitHub profile and follows these conventions:

- **Professional Identity**: DevOps & Cloud Architect, Platform Engineer, AI Infrastructure Specialist
- **Current Focus**: Multi-cloud AI infrastructure, MCP server development, multi-agent systems, GitOps
- **Core Sections**: About, Core Expertise, Tech Stack, GitHub Activity (with stats widgets), Beyond Code
- **Style**: Structured with tables, centered elements, inline code blocks, and embedded GitHub stats widgets

### GitHub Stats Widgets

The profile uses several dynamic stat widgets that auto-update:
- `github-readme-stats.vercel.app` - GitHub statistics and language breakdown
- `github-readme-streak-stats.herokuapp.com` - Contribution streak
- `github-readme-activity-graph.vercel.app` - Activity graph
- `github-profile-trophy.vercel.app` - Achievement trophies
- `metrics.lecoq.io` - Detailed metrics

These widgets use URL parameters for theming (transparent/github-compact themes, hide_border=true).

### HTML Comments for Auto-Updates

The README includes HTML comment markers for automated content injection:
- `<!--START_SECTION:activity-->` / `<!--END_SECTION:activity-->` - Latest GitHub activity (likely updated via GitHub Actions)
- `<!-- BLOG-POST-LIST:START -->` / `<!-- BLOG-POST-LIST:END -->` - Blog posts section (currently commented out)

## Images

All images are stored in `/img/` and should maintain consistent theming with the profile's technical/fantasy aesthetic:
- Profile icons (favicon.png, logo.png)
- Technical imagery (rj45.png, vim.png)
- Fantasy/gaming references (drizzt.jpg, rorschach.png, zelda.png)
- UI elements (colors.png, welcome.png)

## GitHub Profile Best Practices (2026)

### Core Principles

**Dynamic Content Over Static**: Profiles that auto-update with real-time data (GitHub stats, contributions, activity feeds) are significantly more engaging than static bios. This profile already implements this with multiple stat widgets.

**Visual Hierarchy & Readability**:
- Lead with a clear professional identity statement
- Use modular sections with distinct purposes
- Balance visual elements with substantive content
- Maintain consistent theming across all components

**Automation First**: Leverage GitHub Actions for self-updating content rather than manual maintenance. The HTML comment markers (`<!--START_SECTION:activity-->`) enable this.

### Essential Requirements (GitHub Official)

For the profile README to display correctly:
1. Repository name must exactly match GitHub username (`cosckoya`)
2. Repository must be public
3. README.md must be in the root directory
4. README.md must contain content (empty files won't display)

### Current Trends & Tools

**Popular Dynamic Widgets**:
- GitHub Readme Stats (78k+ stars) - statistics and language breakdown
- GitHub Streak Stats (6.5k+ stars) - contribution streaks
- GitHub Profile Trophy - achievement visualization
- Metrics (16k+ stars) - comprehensive metrics dashboards
- Readme Typing SVG (8k+ stars) - animated text effects

**Automation Tools**:
- `blog-post-workflow` - Auto-sync blog posts
- `waka-readme-stats` - Coding activity from WakaTime
- `profile-summary-cards` - Multi-metric dashboards
- GitHub Actions workflows for scheduled updates

### Content Strategy

**Show, Don't Just Tell**:
- Link to live projects and deployed applications
- Embed visual previews and screenshots
- Use badges for skills but balance with depth
- Include real metrics over self-assessed skill levels

**Professional + Personal Balance**: The most effective 2026 profiles combine:
- Clear professional credibility and expertise
- Authentic personal voice and interests
- Visual style reflecting individual identity
- Strategic calls-to-action (star repos, connect, collaborate)

**Responsive Design**: Consider dark/light mode compatibility and mobile viewing. The transparent theme approach used in this profile adapts well across contexts.

### Advanced Patterns

**Multi-Platform Integration**:
- Stack Overflow activity
- Blog post feeds (Medium, Dev.to)
- Social media presence
- Contribution to open source projects

**Interactive Elements**:
- Collapsible sections with `<details>` tags (already used for "More Statistics")
- Clickable tables of contents
- Badge ecosystems linking to profiles/docs
- SVG animations and custom graphics

### Common Pitfalls to Avoid

**Over-Engineering**:
- Don't add every possible stat widget (causes visual clutter)
- Avoid excessive GIFs and animations (can appear unprofessional)
- Don't list every technology ever touched (focus on current expertise)

**Maintenance Failures**:
- Broken image links (test all images after adding)
- Dead external widget URLs (verify services are reliable)
- Outdated information (use automation to prevent this)
- Manual sections becoming stale (automate or remove)

**Readability Issues**:
- Wall of badges with no context
- Excessive use of emojis
- Inconsistent formatting or theming
- Mobile-unfriendly layouts (especially large tables)

**Visibility Requirements**:
- Repository becoming private (makes README disappear)
- Empty or deleted README file (profile won't display)
- Repository name mismatch with username (must be exact match)

**Professional Concerns**:
- Too casual for professional context (balance personality with professionalism)
- No clear call-to-action or contact method
- Generic template content without customization
- Lack of substance behind visual appeal

## Potential Enhancements

Based on 2026 best practices, consider these improvements:

### GitHub Actions Automation

**Activity Updates**: The `<!--START_SECTION:activity-->` markers suggest a workflow for updating recent GitHub activity. If not already implemented, use:
- `gautamkrishnar/blog-post-workflow` - Auto-updates activity section
- Schedule: Daily or on push to keep content fresh

**Blog Post Integration**: The commented-out `<!-- BLOG-POST-LIST:START -->` section could be activated with:
- RSS feed from personal blog or Medium
- Automatic updates via GitHub Actions
- No manual maintenance required

**WakaTime Stats**: Add coding activity statistics:
- Weekly language breakdown
- Total coding hours
- Most active times

### Additional Widgets to Consider

**3D Contribution Graph**: `github-profile-3d-contrib` provides novel visualization of contribution patterns

**Spotify Now Playing**: Real-time display of currently playing music (personal touch aligning with "Beyond Code" section)

**Skill Badges**: Shields.io badges for specific technologies mentioned in Tech Stack (Python, TypeScript, Kubernetes, etc.)

**Recent Blog Posts**: If maintaining a technical blog, auto-sync latest posts

### Content Additions

**Pinned Repositories Section**: Highlight 3-4 key projects with:
- Brief descriptions
- Tech stack used
- Links to live demos
- Repository cards with stats

**Contact Methods**: Add professional contact options:
- LinkedIn profile link
- Professional email
- Calendly for meetings
- Discord/Slack community links

**Call-to-Action**: Add specific CTAs like:
- "📫 Open to consulting opportunities"
- "🤝 Available for collaborations on X, Y, Z"
- "⭐ Check out my pinned repositories"

## Editing Guidelines

When updating this profile:

1. **Maintain Professional Tone**: Balance technical expertise with personal interests (DevOps + fantasy/gaming)
2. **Keep Structure**: Preserve the section hierarchy and visual layout
3. **Test Widget URLs**: Ensure all external stat widgets render correctly before committing
4. **Respect Theme**: Maintain transparent theme with `hide_border=true` for cohesive appearance
5. **Update Stats Markers**: Don't remove HTML comment markers used for automated updates
6. **Prioritize Automation**: When adding new dynamic content, prefer GitHub Actions workflows over manual updates
7. **Visual Consistency**: New images in `/img/` should align with the technical/fantasy aesthetic
8. **Link Strategy**: External links should open relevant profiles, projects, or documentation
9. **Mobile-Friendly**: Test layout with different viewport widths
10. **Semantic HTML**: Use appropriate HTML in markdown where needed (centering, tables, collapsible sections)

## Quick Reference: Tools & Resources

### Dynamic Stats & Widgets

- **GitHub Readme Stats**: `https://github-readme-stats.vercel.app/api?username=USERNAME&params`
- **Streak Stats**: `https://github-readme-streak-stats.herokuapp.com/?user=USERNAME&params`
- **Activity Graph**: `https://github-readme-activity-graph.vercel.app/graph?username=USERNAME&params`
- **Profile Trophy**: `https://github-profile-trophy.vercel.app/?username=USERNAME&params`
- **Metrics**: `https://metrics.lecoq.io/USERNAME?template=classic&params`
- **3D Contributions**: `https://github.com/yoshi389111/github-profile-3d-contrib`

### GitHub Actions Workflows

- **Blog Post Workflow**: `gautamkrishnar/blog-post-workflow`
- **WakaTime Stats**: `anmol098/waka-readme-stats`
- **Recent Activity**: `jamesgeorge007/github-activity-readme`
- **Profile Summary Cards**: `vn7n24fzkq/github-profile-summary-cards`

### Design Tools

- **Shields.io**: Custom badges for tech stack (`https://shields.io/`)
- **Simple Icons**: Tech logos for badges (`https://simpleicons.org/`)
- **Readme Typing SVG**: Animated text (`https://readme-typing-svg.herokuapp.com/`)
- **Capsule Render**: Custom headers (`https://github.com/kyechan99/capsule-render`)

### Collections & Inspiration

- **Awesome GitHub Profile README**: `abhisheknaiidu/awesome-github-profile-readme`
- **Creative Profile README**: `coderjojo/creative-profile-readme`
- **GitHub Topics**: `github.com/topics/profile-readme` (4,600+ repos)

### Testing & Validation

- **GitHub Markdown Preview**: Use repository preview before committing
- **Dark/Light Mode**: Test theme toggle in GitHub settings
- **Mobile View**: Use browser responsive design mode
- **Widget Parameters**: Test URL parameters in browser before embedding
