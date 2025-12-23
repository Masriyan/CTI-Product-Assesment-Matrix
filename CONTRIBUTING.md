# Contributing to CTI Product Assessment Matrix

Thank you for your interest in contributing to the CTI Product Assessment Matrix! This document provides comprehensive guidelines for contributing to this project.

---

## 📋 Table of Contents

- [How to Contribute](#how-to-contribute)
- [Enhanced Assessment Template](#enhanced-assessment-template)
- [Quality Guidelines](#quality-guidelines)
- [Source Requirements](#source-requirements)
- [Writing Style Guide](#writing-style-guide)
- [What NOT to Include](#what-not-to-include)
- [Code of Conduct](#code-of-conduct)
- [Review Process](#review-process)
- [Vendor Participation](#vendor-participation)

---

## 🤝 How to Contribute

### Reporting Inaccuracies or Updates

If you notice outdated information or inaccuracies:

1. **Open an Issue**
   - Use the "Inaccuracy Report" issue template
   - Describe the specific inaccuracy
   - Include the product name and section

2. **Provide Sources**
   - Include 2-3 reliable sources for the correct information
   - Prefer official vendor documentation or analyst reports
   - Include URLs and access dates

3. **Submit**
   - Maintainers will review within 7 days
   - You may be asked for additional clarification

### Adding New Products

To suggest a new CTI product for inclusion:

1. **Eligibility Check**
   - Product must be enterprise-grade OR have significant market presence
   - Minimum 50 enterprise customers OR recognized by major analysts (Gartner, Forrester, IDC)
   - Must have publicly available information for assessment

2. **Tier Classification**
   - Identify appropriate tier (1-6 or Regional)
   - Justify tier placement based on capabilities and market position

3. **Initial Research**
   - Gather 10+ sources of public information
   - Include official documentation, analyst reports, customer reviews
   - Document pricing (if publicly available)

4. **Submit Proposal**
   - Open issue with "New Product Suggestion" label
   - Include preliminary research and sources
   - Proposed tier classification with justification

### Updating Existing Assessments

To update an existing product assessment:

1. **Fork the Repository**
   ```bash
   git fork https://github.com/Masriyan/CTI-Product-Assesment-Matrix.git
   ```

2. **Create Branch**
   ```bash
   git checkout -b update-[product-name]-[date]
   # Example: git checkout -b update-recorded-future-2025-01
   ```

3. **Make Changes**
   - Follow the enhanced template structure (see below)
   - Maintain all required sections
   - Update sources and references
   - Update "Last Updated" field

4. **Quality Check**
   - [ ] All sections complete
   - [ ] 15-20 sources included
   - [ ] Capability matrix updated
   - [ ] Comparison tables accurate
   - [ ] No promotional language
   - [ ] Neutral, objective tone

5. **Submit Pull Request**
   - Clear description of changes
   - List sources used for updates
   - Reference any related issues

---

## 📝 Enhanced Assessment Template

Each product assessment must follow this comprehensive structure:

### Required Sections

```markdown
# [Product Name]

## 📋 Overview
**Vendor:** [Company Name]
**Headquarters:** [City, Country]
**Founded:** [Year]
**Website:** [URL]

[2-3 paragraph description of product and company]

---

## 🎯 Capability Matrix

| Category | Rating | Notes |
|----------|--------|-------|
| **Threat Intelligence Coverage** | ⭐⭐⭐⭐⭐ | [Brief note] |
| **Machine Learning/AI** | ⭐⭐⭐⭐ | [Brief note] |
| **Integration Ecosystem** | ⭐⭐⭐⭐⭐ | [Brief note] |
| **User Interface** | ⭐⭐⭐⭐ | [Brief note] |
| **API Quality** | ⭐⭐⭐⭐⭐ | [Brief note] |
| **Pricing** | ⭐⭐⭐ | [Brief note - inverse rating] |
| **Customer Support** | ⭐⭐⭐⭐ | [Brief note] |
| **Deployment Speed** | ⭐⭐⭐⭐ | [Brief note] |

---

## 🔑 Key Features

### Core Intelligence Capabilities
| Feature | Description | Availability |
|---------|-------------|--------------|
| **Feature 1** | Description | Tier/Availability |
| **Feature 2** | Description | Tier/Availability |

### Intelligence Types
- **Strategic Intelligence**: [Description]
- **Operational Intelligence**: [Description]
- **Tactical Intelligence**: [Description]
- **Technical Intelligence**: [Description]

---

## ✅ Strengths

### Technical Advantages
- ✓ **Point 1**: Detailed explanation
- ✓ **Point 2**: Detailed explanation

### Operational Benefits
- ✓ **Point 1**: Detailed explanation
- ✓ **Point 2**: Detailed explanation

---

## ❌ Limitations

### Technical Challenges
- ✗ **Point 1**: Detailed explanation
- ✗ **Point 2**: Detailed explanation

### Business Constraints
- ✗ **Point 1**: Detailed explanation
- ✗ **Point 2**: Detailed explanation

---

## 💼 Use Cases

### Primary Use Cases
1. **Use Case 1**
   - Sub-point 1
   - Sub-point 2

### Industry Applications
- **Industry 1**: Specific applications
- **Industry 2**: Specific applications

---

## 🔗 Integration Capabilities

### Native Integrations

| Category | Supported Products |
|----------|-------------------|
| **SIEM** | List products |
| **SOAR** | List products |
| **EDR/XDR** | List products |

### API & Standards Support
- API details
- Standards compliance
- SDKs available

---

## 💰 Pricing Model

### Licensing Structure

| Tier | Target Audience | Typical Annual Cost | Key Features |
|------|----------------|---------------------|--------------|
| **Tier 1** | Description | $X - $Y | Features |

### Pricing Factors
- Factor 1
- Factor 2

---

## 🏢 Target Organization Profile

### Organization Size
- **Optimal**: [Size]
- **Minimum**: [Size]

### Industry Fit
✅ **Highly Suitable**: [Industries]
⚠️ **Moderately Suitable**: [Industries]
❌ **Less Suitable**: [Industries]

---

## 📊 Competitive Positioning

### vs. [Competitor 1]
- **Product Advantage**: [Details]
- **Competitor Advantage**: [Details]

---

## 📚 Sources and References

### Analyst Reports
1. [Analyst Report 1 with annotation]
2. [Analyst Report 2 with annotation]

### Vendor Resources
[List 3-5 official sources]

### Customer Reviews & Ratings
[List 2-3 review platforms with scores]

### Industry Publications
[List 3-5 industry sources]

### Technical Documentation
[List 2-3 technical resources]

**Minimum 15 sources required, 20+ recommended**

---

## 🔄 Recent Updates & Developments
[Major changes in last 12 months]

---

## 📈 Market Position
[Market share, customer base, analyst positioning]

---

## ⚡ Quick Decision Matrix

| Your Situation | Recommendation |
|----------------|----------------|
| Scenario 1 | ✅/⚠️/❌ Recommendation |

---

## 📅 Last Updated
[Month Year]

---

## 📝 Assessment Methodology
[Standard methodology note]
```

---

## ✅ Quality Guidelines

### Objectivity Standards

#### ✅ DO
- Maintain neutral, factual tone throughout
- Present balanced view with both strengths and weaknesses
- Base all claims on verifiable sources
- Use specific examples and data points
- Clearly distinguish fact from interpretation
- Acknowledge limitations in available data

#### ❌ DON'T
- Use promotional or marketing language
- Make unsupported claims
- Show bias toward or against vendors
- Include personal opinions without factual basis
- Exaggerate capabilities or limitations
- Make absolute statements without qualification

### Accuracy Requirements

1. **Currency**
   - Information must be current (within 12 months)
   - Older information must be clearly marked
   - Update "Last Updated" field when making changes

2. **Verification**
   - Cross-reference 3+ sources for factual claims
   - Prioritize primary sources (vendor docs, analyst reports)
   - Include source URLs with access dates

3. **Precision**
   - Use specific numbers when available
   - Provide ranges when exact data unavailable
   - Clearly mark estimates as such

### Completeness Standards

- All template sections must be filled
- Minimum 15 sources (20+ recommended)
- Complete capability matrix (all 8 categories)
- At least 3 use cases described
- Integration table with 5+ categories
- Pricing information (or note if unavailable)

---

## 📚 Source Requirements

### Source Quality Hierarchy

**Tier 1 Sources** (Highest Priority)
- Industry analyst reports (Gartner, Forrester, IDC)
- Official vendor documentation and datasheets
- Peer-reviewed academic papers
- Government/regulatory filings

**Tier 2 Sources** (High Priority)
- Customer review platforms (Gartner Peer Insights, G2, TrustRadius)
- Reputable industry publications (Dark Reading, SC Magazine, CSO)
- Technical documentation and API specs
- Vendor blog posts and research papers

**Tier 3 Sources** (Supporting)
- Industry news articles
- Conference presentations
- Webinars and whitepapers
- Social media (for updates only, not primary claims)

### Source Attribution Format

```markdown
1. [Source Title](URL) - *Additional context, rating, or date*
```

Example:
```markdown
1. [Gartner Magic Quadrant for Security Threat Intelligence, 2024](https://www.gartner.com/...) - *Leader Quadrant*
2. [Customer Reviews - G2](https://www.g2.com/products/...) - *4.5/5 (200+ reviews)*
```

### Minimum Source Requirements by Section

- Overview: 2-3 sources
- Capability Matrix: 3-5 sources
- Features: 3-5 sources
- Strengths/Limitations: 5-7 sources
- Integration: 2-3 sources
- Pricing: 2-3 sources (if available)
- Competitive Analysis: 2-3 sources per comparison

---

## ✍️ Writing Style Guide

### Language Standards

1. **Clarity**
   - Use plain language; avoid unnecessary jargon
   - Define technical terms on first use
   - Keep sentences concise (15-25 words average)
   - One main idea per paragraph

2. **Consistency**
   - Use consistent terminology throughout
   - Maintain uniform formatting
   - Apply standard abbreviations
   - Follow template structure exactly

3. **Voice**
   - Use active voice primarily
   - Third person perspective
   - Present tense for current features
   - Past tense for historical information

### Formatting Standards

- Use **bold** for emphasis on key terms
- Use *italics* for annotations and notes
- Use ✓/✗ symbols for pros/cons
- Use ⭐ for ratings (1-5 stars)
- Use emojis consistently per template
- Use markdown tables for comparisons

### Word Count Guidelines

- Overview: 150-250 words
- Each feature description: 20-50 words
- Each strength/limitation: 30-60 words
- Use case descriptions: 40-80 words each
- Total assessment: 2,000-4,000 words

---

## 🚫 What NOT to Include

### Prohibited Content

❌ **Personal Opinions**
- "I think this is the best platform"
- "In my experience..."
- Unsubstantiated preferences

❌ **Unverified Claims**
- Rumors or speculation
- Unconfirmed roadmap features
- Unofficial pricing information

❌ **Sensitive Information**
- Confidential customer data
- Non-public pricing details
- Proprietary technical specifications
- Security vulnerabilities (unless publicly disclosed)

❌ **Promotional Content**
- Marketing hype or exaggeration
- Competitive disparagement
- Sales-oriented language
- Affiliate links

❌ **Absolute Comparisons**
- "Best platform for..."
- "Better than X in every way"
- Definitive rankings without context

### Acceptable Alternatives

✅ Instead of: "This is the best threat intelligence platform"
Write: "Rated as a Leader in Gartner Magic Quadrant 2024"

✅ Instead of: "Very expensive"
Write: "Premium pricing tier ($100K-250K annually)"

✅ Instead of: "Easy to use"
Write: "User-friendly interface with 4.5/5 usability rating on G2"

---

## 🤝 Code of Conduct

### Our Commitments

We pledge to make participation in this project a harassment-free experience for everyone, regardless of:
- Age, body size, disability, ethnicity
- Gender identity and expression
- Level of experience, education, socio-economic status
- Nationality, personal appearance, race, religion
- Sexual identity and orientation

### Expected Behavior

✅ **DO:**
- Use welcoming and inclusive language
- Be respectful of differing viewpoints
- Accept constructive criticism gracefully
- Focus on what's best for the community
- Show empathy toward others

❌ **DON'T:**
- Use sexualized language or imagery
- Make derogatory comments or personal attacks
- Engage in trolling or insulting behavior
- Publish others' private information
- Act unprofessionally

### Enforcement

Violations of code of conduct will result in:
1. **Warning**: First offense, private discussion
2. **Temporary Ban**: Repeat offenses, 30-day ban
3. **Permanent Ban**: Severe or persistent violations

---

## 🔍 Review Process

### Submission Review Timeline

| Stage | Timeline | Actions |
|-------|----------|---------|
| **Initial Review** | 3-7 days | Completeness check, template compliance |
| **Technical Review** | 5-10 days | Fact-checking, source verification |
| **Quality Review** | 3-5 days | Writing quality, objectivity assessment |
| **Final Approval** | 1-3 days | Final edits and merge |

### Review Criteria

Submissions are evaluated on:

1. **Completeness** (25%)
   - All template sections filled
   - Minimum source requirements met
   - All tables and matrices complete

2. **Accuracy** (30%)
   - Facts verified across multiple sources
   - No contradictions or errors
   - Current information (within 12 months)

3. **Objectivity** (25%)
   - Neutral tone throughout
   - Balanced strengths/limitations
   - No promotional language

4. **Quality** (20%)
   - Clear, professional writing
   - Proper grammar and formatting
   - Consistent with style guide

### Feedback Process

- Reviewers may request changes
- Contributors have 14 days to address feedback
- Constructive discussion encouraged
- Final decision by maintainers

### Recognition

- Contributors acknowledged in commit history
- Significant contributors recognized in README
- Optional contributor badge available

---

## 🏢 Vendor Participation

### Vendors Are Welcome To:

✅ **Suggest Corrections**
- Report factual errors about your product
- Provide updated documentation links
- Notify of major product changes or rebranding
- Share public case studies or testimonials

✅ **Provide Information**
- Publicly available product information
- Links to official documentation
- Analyst report references
- Customer references (with permission)

### Vendors Should NOT:

❌ **Direct Editing**
- Write or substantially edit your own assessment
- Remove legitimate criticism or limitations
- Add promotional content or marketing language

❌ **Influence Review**
- Request favorable treatment
- Offer compensation for positive coverage
- Pressure for competitor disparagement

### Vendor Submission Guidelines

1. **Identify Yourself**
   - Disclose vendor affiliation clearly
   - Provide official contact information
   - Use company email for correspondence

2. **Provide Documentation**
   - Official links to updated information
   - Public announcements or press releases
   - Analyst report citations

3. **Accept Independent Review**
   - All vendor submissions independently verified
   - Vendor contributions clearly marked
   - No guarantee of inclusion/modification

### Handling Vendor Feedback

- Vendor-submitted corrections reviewed within 14 days
- Independent verification required for all changes
- Vendor contributions noted in assessment
- Transparency maintained throughout process

---

## 📋 Contribution Checklist

Before submitting your contribution:

### Content Checklist
- [ ] All template sections complete
- [ ] 15-20 trusted sources included
- [ ] Capability matrix with 8 categories rated
- [ ] Feature tables with availability tiers
- [ ] Integration table with 5+ categories
- [ ] Pricing information (or note if unavailable)
- [ ] Competitive positioning section
- [ ] Quick decision matrix
- [ ] "Last Updated" field current

### Quality Checklist
- [ ] Neutral, objective tone throughout
- [ ] No promotional or marketing language
- [ ] All claims sourced and verifiable
- [ ] No personal opinions without factual basis
- [ ] Grammar and spelling checked
- [ ] Markdown formatting correct
- [ ] Links tested and working

### Source Checklist
- [ ] Minimum 15 sources (20+ recommended)
- [ ] Mix of analyst reports, vendor docs, reviews
- [ ] All sources publicly accessible
- [ ] Source URLs include descriptions/annotations
- [ ] Sources dated within 12 months (or marked as historical)

---

## 💡 Tips for Quality Contributions

1. **Start with Research**
   - Gather 20-30 sources before writing
   - Read multiple analyst reports
   - Review customer feedback on 2-3 platforms

2. **Use Templates**
   - Copy enhanced template exactly
   - Don't skip sections
   - Maintain formatting consistency

3. **Be Specific**
   - Use concrete examples
   - Include specific numbers and data
   - Avoid vague generalizations

4. **Stay Current**
   - Verify information is recent
   - Check for recent product updates
   - Note if using older information

5. **Get Feedback**
   - Ask for peer review before submitting
   - Test readability with non-experts
   - Check technical accuracy with experts

---

## 📞 Questions?

If you have questions about contributing:

- Open an issue with "question" label
- Email maintainers (if contact provided)
- Join community discussions
- Review existing assessments as examples

---

## 🙏 Thank You!

Thank you for helping make this resource valuable for the cybersecurity community! Your contributions help security professionals make informed decisions about threat intelligence platforms.

---

**Last Updated**: December 2025
**Version**: 2.0 (Enhanced Format)
