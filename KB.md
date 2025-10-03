# Pattaconk Polissoir Podcast - Knowledge Base

## Project Identity

**Name**: The Pattaconk Polissoir Podcast
**Location**: Summit of Turkey Hill (79 Turkey Hill Road, Chester, CT)
**Format**: Live 4K interactive tech podcast with call-ins
**Unique Position**: Broadcasting from an ancient archaeological/geological site

## Core Narrative

### The Mystery
Ancient grooves in bedrock on the summit represent either:
1. **Polissoir**: Native American stone tool sharpening station (human craftsmanship)
2. **Glacial Channel**: Ice age meltwater erosion under continental ice (geological force)

### The Convergence
Three timelines meet at this location:
- **Deep Time**: Glacial geology (15,000+ years ago)
- **Ancient History**: Native American inhabitants (unknown - ~400 years ago)
- **Modern Era**: Live 4K streaming, AI technology (now)

## Infrastructure

### AWS Architecture
- **S3 Bucket**: `pattaconk-polissoir`
  - Static website hosting enabled
  - Public read access configured
  - Index: index.html, Error: error.html

- **CloudFront Distribution**: `EPDD9G8JXDVGT`
  - Domain: https://dok3le6kfwcxx.cloudfront.net
  - HTTPS redirect enabled
  - Compression enabled
  - Status: InProgress (deploying)

- **GitHub Actions Deployment**
  - Workflow: `.github/workflows/deploy.yml`
  - Triggers: Push to main/master
  - Excludes: .git, .github, *.md, private/*
  - Invalidates CloudFront cache on deploy

### Broadcast Infrastructure
- **Internet**: 500+ Mbps upstream (enterprise-grade)
- **Control Shack**: 40 ft from firepit
- **Power**: Dedicated buried electrical line
- **Firepit**: 8-foot diameter centerpiece
- **Cameras**: Multi-iPhone 4K setup
- **Audio**: Professional multi-channel

## Episode One Structure

### Act 1: The Discovery
- Site clearing documentation
- Uncovering the grooves
- Initial research and theories

### Act 2: The Expert Visit
- Mr. Perreault (local historian) on-site examination
- Forensic analysis: U-shaped vs V-shaped grooves
- Texture analysis: polished smooth vs rough/scraped
- Expert conclusion

### Act 3: The Inaugural Fire
- First live broadcast from site
- Dedication honoring the history
- Setting mission for the show

## Key Collaborator

**Mr. Perreault**
- Renowned local Native American historian
- Retired teacher with Connecticut tribal knowledge
- Prior collaboration: 4K productions for Chester Historical Society
- Role: Forensic analyst and detective for Episode One

## Technical Specifications

### Location
- **Address**: 79 Turkey Hill Road, Chester, CT
- **Status**: GPS-confirmed summit
- **Site**: Flat, sheltered bedrock nook

### Broadcast Capabilities
- **Video**: 4K streaming
- **Audio**: Multi-channel professional
- **Interaction**: Live call-ins, real-time chat
- **Timing**: Golden hour + twilight opening

## Budget Estimates

### Infrastructure Investment
- Firepit construction: $500-1000
- Buried power line: $1000-2000
- Control shack: $500-1500
- Weather protection: $300-500
- **Total**: $2,300-5,000

### Free Assets
- Location (owned)
- Internet (installed)
- Equipment (iPhone 4K multi-cam owned)
- Expert collaboration (relationship established)

## Project Timeline

### Immediate Actions
1. Site documentation (4K video, photos)
2. Contact Mr. Perreault
3. Research Pattaconk name verification

### Pre-Production
1. Episode One planning and scripting
2. Technical testing (streaming, audio)
3. Infrastructure build (firepit, control shack)

### Production
1. Documentary footage (three acts)
2. Live broadcast element
3. Post-production and editing

### Launch
1. Episode One release
2. Marketing campaign ("mystery on the summit")
3. Community engagement

## Mission Statement

"The Pattaconk Polissoir Podcast is a live, interactive technology podcast broadcast from a summit with a mystery. We explore modern tech, AI, and human creativity from a place where time converges—where ancient grooves in the stone tell a story we're still learning to read. Every episode starts at the firepit, but where we go from there depends on you."

## Success Metrics

### Episode One Goals
- Credible mystery documentation
- Expert legitimacy established
- Community interest generated
- Viral-potential content created

### Long-term Goals
- Build audience around convergence theme
- Establish Turkey Hill summit as landmark
- Create revenue-generating podcast
- Honor the history of the place

## Repository Structure

```
pattaconk-polissoir/
├── index.html              # Public website
├── assets/                 # Images, logos, media
├── private/                # Internal docs (excluded from deployment)
│   └── PROJECT-BRIEF.md    # Comprehensive planning document
├── .github/workflows/
│   └── deploy.yml          # Automated deployment
├── README.md               # Project overview
└── KB.md                   # This knowledge base
```

## Deployment Process

1. Push changes to main branch
2. GitHub Actions triggers
3. Syncs to S3 (excludes private/*, *.md, .git/*, .github/*)
4. Invalidates CloudFront cache
5. Changes live within minutes

## Contact Information

**Host**: Jon Claude Haines
**Email**: contact@jonclaude.net
**Location**: 79 Turkey Hill Road, Chester, CT
**GitHub**: jonclaudedotnet/pattaconk-polissoir

---

**Knowledge Base Status**: Complete and current as of 2025-10-03
**Last Updated**: Initial infrastructure deployment
**Next Review**: After Episode One production begins
