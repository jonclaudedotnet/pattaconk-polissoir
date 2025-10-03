# The Pattaconk Polissoir Podcast

> Broadcasting from the summit of Turkey Hill, where Deep Time meets Modern Technology

## Overview

The Pattaconk Polissoir Podcast is a live, interactive technology podcast broadcast from an ancient site on the summit of Turkey Hill in Chester, Connecticut. The show explores modern tech, AI, and human creativity from a place where time converges—where mysterious grooves in bedrock tell a story we're still learning to read.

## The Mystery

Ancient grooves carved into bedrock on the summit tell one of two stories:

- **Hypothesis A**: A polissoir—a sacred Native American worksite where stone tools were sharpened for generations
- **Hypothesis B**: A glacial meltwater channel carved 15,000 years ago under a mile of ice

Episode One will be a live investigation with a local historian to solve the mystery.

## Technical Setup

- **4K Live Streaming** from outdoor studio
- **500+ Mbps Upload** for flawless quality
- **Interactive Call-Ins** for audience participation
- **Multi-Camera Production** with professional audio

## Infrastructure

- **S3 Bucket**: `pattaconk-polissoir`
- **CloudFront Distribution**: `EPDD9G8JXDVGT`
- **Domain**: https://dok3le6kfwcxx.cloudfront.net
- **GitHub Actions**: Automated deployment on push to main

## Project Structure

```
pattaconk-polissoir/
├── index.html              # Public website
├── assets/                 # Images, logos, media
├── private/                # Internal planning docs (not deployed)
│   └── PROJECT-BRIEF.md    # Comprehensive project brief
├── .github/workflows/
│   └── deploy.yml          # Automated S3 + CloudFront deployment
└── README.md               # This file
```

## Deployment

Changes to `main` branch automatically deploy to S3 and invalidate CloudFront cache via GitHub Actions.

**Note**: The `private/` directory is excluded from deployment and contains internal planning documents.

## Contact

Jon Claude Haines
contact@jonclaude.net
79 Turkey Hill Road, Chester, CT

---

*"We found marks in the stone. Here's what they might be. Let's find out together."*
