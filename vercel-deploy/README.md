---
title: Deploy to Vercel
description: Build and deploy a web application to Vercel production environment.
author: Buildkite
languages: ["JavaScript"]
use_cases: ["CD", "Web"]
platforms: ["Vercel"]
tools: ["Next.js"]
primary_emojis: [":vercel:"]
---

# Deploy to Vercel

This templates gives you a continuous deployment (CD) pipeline that builds and deploys a web application to Vercel.

At a glance:

- For [Vercel](https://vercel.com/) web applications
- Uses [npm](https://www.npmjs.com/)
- Uses [Vercel CLI](https://vercel.com/docs/cli)

## How it works

This template:

1. Installs the Vercel CLI using npm.
2. Pulls production Vercel environment information.
3. Builds an application for production, outputting a `.vercel/output` folder, which is available as an [artifact](https://buildkite.com/docs/pipelines/artifacts).
4. Deploys the prebuilt application to Vercel production environment.

## Next steps

After you select **Use template**, you’ll:

1. Connect the Git repository with your Vercel application.
2. Configure Buildkite with the following secrets: `VERCEL_TOKEN`, `VERCEL_ORG_ID`, `VERCEL_PROJECT_ID`.
3. Configure the compute—run locally, on-premises, or in the cloud.
4. Run the pipeline.

You can then play around with the pipeline settings. For example, run the pipeline locally while you iterate on the definition or set a schedule to trigger a nightly build.

If you need help, please [check our documentation](https://buildkite.com/docs/pipelines/configuration-overview), [raise an issue](https://github.com/buildkite/templates/issues), or [reach out to support](https://buildkite.com/support).
