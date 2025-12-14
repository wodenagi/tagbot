# PR Tagger - Automated Pull Request Intelligence

## The Problem

Reviewers struggle to assess pull requests quickly. Without context on size, complexity, and risk, teams waste time evaluating scope, miss high-risk changes, and struggle to prioritize reviews effectively. This slows development velocity and increases the chance of issues reaching production.

## The Solution

PR Tagger automatically analyzes every pull request and provides instant insights through intelligent labels and detailed analysis. Teams understand the scope, complexity, and risk of changes at a glance, enabling faster, more effective code reviews.

**Completely free** - no token limits, usage caps, or hidden costs.

---

## Key Features

- **Automatic Label Generation**: Size (small/medium/large/XL), complexity (0-10 scale), risk level (low/medium/high), type (feature/bugfix/refactor)
- **Smart Analysis**: Documentation detection, impact assessment, risk mitigation for high-risk PRs
- **Professional PR Comments**: Detailed breakdown with visual badges, email-friendly formatting, collapsible sections
- **Language Detection**: Automatically identifies primary languages used in changes
- **Zero Configuration**: Install and forget - works immediately on all PRs with no setup or maintenance
- **Completely Free**: No token limits, usage caps, or hidden costs

## Pricing

PR Tagger is **100% free** with no token limits, usage caps, or hidden costs. Install once and benefit forever.

## Setup

### Quick Installation (1 minute)

1. **[Install PR Tagger](https://github.com/apps/pr-insights-tagger)** on your repository
2. Open a pull request
3. Analysis appears automatically in seconds
4. No configuration needed

**For advanced configuration options**, visit the [setup guide](https://woden-ai.com/setup/tagger).

## How It Works

### Automatic Analysis

PR Tagger analyzes every pull request automatically:

1. **Label Generation**: Adds size, complexity, risk, and type labels to the PR
2. **Detailed Comment**: Posts comprehensive analysis with visual badges and metrics
3. **Email Notifications**: Analysis appears in GitHub notification emails with proper formatting
4. **Risk Highlighting**: High-risk PRs are flagged for extra review attention

### Privacy & Security

- Code analyzed in real-time, never stored
- GitHub native - works within GitHub's security model
- Minimal permissions (PR read access, label/comment write)
- Open source friendly with fully transparent operation

### Example Analysis

```
## PR Analysis Summary

![Risk Level](https://img.shields.io/badge/Risk-MEDIUM-yellow)
![Complexity](https://img.shields.io/badge/Complexity-6/10-blue)
![Files Changed](https://img.shields.io/badge/Files-8-informational)

### Change Metrics
| Metric | Value |
|:-------|------:|
| Lines Added | +368 |
| Lines Deleted | -164 |
| Files Modified | 8 |
| Complexity Score | 6/10 |
| Risk Assessment | MEDIUM |

### Classification
`feature` `frontend` `typescript`

### Files by Type
**typescript**  5 files (+342, -156)
**css**         2 files (+18, -8)
**markdown**    1 file (+8, -0)

### Risk Factors
- Multiple core files modified
- Significant logic changes detected
- Moderate file diversity (3 languages)

---
Analysed by **Woden Tagger**
```

## Support

- **Setup Guide**: [Setup Guide](https://woden-ai.com/setup/tagger)
- **Support & Feature Requests**: [GitHub Issues](https://github.com/wodenagi/tagbot/issues) *Response via comments on issues within 7 days*

---

**Get Started**: [Install PR Tagger](https://github.com/apps/pr-insights-tagger)

---

Built by Woden AI · [Website](https://woden-ai.com)
