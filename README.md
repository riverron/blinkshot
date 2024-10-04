<a href="https://www.blinkshot.io">
  <img alt="Blinkshot" src="./public/og-image.png">
  <h1 align="center">Blinkshot</h1>
</a>

<p align="center">
  An open source image generation playground. Powered by Flux through Together.ai.
</p>

## Tech stack

- [Llama 3.1 8B](https://ai.meta.com/blog/meta-llama-3-1/) from Meta for the LLM
- [Llama 3.2 Vision](https://ai.meta.com/blog/meta-llama-3-1/) from Meta for the Vision model
- [Together AI](https://www.dub.sh/together-ai) for LLM inference
- [Sandpack](https://sandpack.codesandbox.io/) for the code sandbox
- [S3](https://aws.amazon.com/s3/) for image storage
- Next.js app router with Tailwind
- Helicone for observability
- Plausible for website analytics

## Cloning & running

1. Clone the repo: `git clone https://github.com/Nutlope/napkins`
2. Create a `.env` file and add your [Together AI API key](https://www.dub.sh/together-ai): `TOGETHER_API_KEY=`
3. Create an S3 bucket and add the credentials to your `.env` file. Follow [this guide](https://next-s3-upload.codingvalue.com/setup) to set them up. All required values are in the `.env.example` file.
4. Run `npm install` and `npm run dev` to install dependencies and run locally

# TODOs

- [ ] Add observability with Helicone
- [ ] Add rate limiting by IP w/ a credit system that resets every 24h
- [ ] Clean up README, make demo vid, and post on X

## Future Tasks

- [ ] Add a CTA to fork the code on GithUb
- [ ] On hover, have a download button
- [ ] Let people play around with resolutions
- [ ] Let people play around with steps
- [ ] Add a description of the app to the footer
- [ ] Add themes
