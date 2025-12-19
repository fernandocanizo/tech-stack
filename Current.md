# Current Tech Stack

## Front-end

### Remix / React Router

Started with Remix, migrated to React Router 7 when they merged projects.

I started using Remix on 2022, after many years doing only backend. Went to the React page and they recommended Remix and Next.js, read some reviews and found out that people despised Next.js and saw no bad mouthing for Remix.

Maybe Next.js stinks more or maybe Remix was still young enough to not have haters.

Anyway, I'm writing this on 2025-12-18 and I have been fighting the framework all these years. I find it convoluted, got to make ugly hacks not related to the problems I need to solve, to make the framework work for me. I'm looking to get out, hence this repo where I'm gonna take notes about my exploration of other technologies for web development.

### Styles

Started with PicoCSS, but soon it got tiny for our project, then switched to DaisyUI, and again it lacked some components, so we switched again to RadixUI.

Since all these are based on TailwindCss, there's that too. It's my understanding that making style frameworks with TailwindCss could ease the work, however I don't see its benefit over plain CSS. I'm looking forward to go back to plain CSS. Sadly I'm not good at styling and nowadays it seems every CSS framework uses TailwindCss, so my search may prove unfruitful.

`react-icons` to have a plethora of images to choose.

## Back-end

An Express.js application connecting to MongoDB and implementing a Graphql API.

## Tooling

We use `tsc` and Biome to lint and prettify code. Lefthook to make git hooks for the quality tools.

Knip to find out stuff not being used.
