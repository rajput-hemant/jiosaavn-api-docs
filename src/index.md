---
order: 10000
icon: rocket
---

<div align=center>

# Introduction

</div>

:::content-center

## JioSaavn API

#### A wrapper for JioSaavn API in Typescript Rust programming language 🦀.

:::

!!! Note
This project is for educational purposes only. The author of this project is not responsible for any misuse of this API. Use it at your own risk.
!!!

---

:::content-center

## ✨ Features

:::

+++ Typescript

- 🚀 **Ultrafast** - Powered by [Hono.js](https://hono.dev).The router `RegExpRouter` is really fast.
- 🪶 **Lightweight** - Has minimal dependencies.
- 🌍 **Multi-runtime** - Works on `Bun`, `Node.js`, `Vercel` or `Cloudflare Workers`. The same code runs on all platforms.
- 🔥 Download High Quality Songs, w/ lyrics for supported songs.
- 🎵 Get Songs, Albums, Playlists, Artists, Radio Stations, Podcasts Lyrics, Recommendations, and more.
- ❤️ Open Source

+++ Rust

- 🚀 **Ultrafast** - Powered by [Axum Web Framework](https://github.com/tokio-rs/axum)
- 🪶 **Lightweight** - Has minimal dependencies.
- 🌍 **Multi-platform** - Supports `Vercel` (using community based [Rust Runtime](https://github.com/vercel-community/rust)) `Docker`, `Render`, `Shuttle.rs` or `Fly.io` and more.
- 🔥 Download High Quality Songs, w/ lyrics for supported songs.
- 🎵 Get Songs, Albums, Playlists, Artists, Radio Stations, Podcasts Lyrics, Recommendations, and more.
- ❤️ Open Source

+++

:::content-center

## 🛠️ Local Development

:::

+++ Typescript

- Clone the repository

```sh
git clone https://github.com/rajput-hemant/jiosaavn-api-ts
cd jiosaavn-api-ts
```

- Install dependencies

#### Bun

!!! warning Warning
You need to have [Bun Runtime](https://bun.sh) installed on your machine to run the project with bun.
!!!

```sh
bun i || pnpm i || yarn || npm i
```

```sh
bun run dev || pnpm dev || yarn dev || npm run dev
```

---

#### Node.js

```sh
bun run dev:node || pnpm dev:node || yarn dev:node || npm run dev:node
```

---

#### Vercel Dev Server

```sh
bun run dev:vercel || pnpm dev:vercel || yarn dev:vercel || npm run dev:vercel
```

---

#### Cloudflare Workers

!!! warning Warning
Make sure to remove Node API code from [`src/index.ts`](https://github.com/rajput-hemant/jiosaavn-api-ts/blob/master/src/index.ts) & [`config.ts`](https://github.com/rajput-hemant/jiosaavn-api-ts/blob/master/src/lib/config.ts#L8) before deploying or running the project with Cloudflare Workers.
!!!

[src/index.ts](https://github.com/rajput-hemant/jiosaavn-api-ts/blob/master/src/index.ts)

```diff
...

-  port: +(process.env.PORT ?? 3000),
+ port: 3000, # update accordingly

...
```

[src/lib/config.ts](https://github.com/rajput-hemant/jiosaavn-api-ts/blob/master/src/lib/config.ts#L8)

```diff
...

-  enableRateLimit: process.env.ENABLE_RATE_LIMIT === "true" ?? false,
+  enableRateLimit: false, # update accordingly
...

```

```sh
bun run dev:vercel || pnpm dev:cf || npm run dev:cf || yarn dev:cf
```

+++ Rust

- Rust should be installed on your system. If not, then install it from [here](https://www.rust-lang.org/tools/install).

```sh
git clone https://github.com/rajput-hemant/jiosaavn-api-rs
cd jiosaavn-api-rs
```

- Run the following command to build the project.

```sh
cargo build --release
```

- Run the following command to launch the api server.

```sh
cargo run --release

```

+++

---

:::content-center

## ☁️ Deploying your own instance

:::

+++ Typescript

:::content-center

### One Click Deploy

:::

You can easily deploy your own hosted version of the `JioSaavn API` by clicking on one of the links below, which will set up a ready-to-go version for you:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/sumitkolhe/jiosaavn-api)
[![Deploy with Cloudflare Workers](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/rajput-hemant/jiosaavn-api-ts)

:::content-center
**OR**

### Deploying using CLI

:::

#### Vercel

- It utilizes Edge Functions and can automatically execute in the region nearest to the user who triggers them.
- It's worth noting that `Mumbai, India (South) - bom1` is the recommended region for this project deployment.

```sh
bun run deploy:vercel || pnpm deploy:vercel || npm run deploy:vercel || yarn deploy:vercel
```

---

#### Cloudfare Workers

```sh
bun run deploy:cf || pnpm deploy:cf || npm run deploy:cf || yarn deploy:cf
```

---

:::content-center

### Build and Run Docker Image

:::

!!!warning Warning
You need to have [Docker](https://docs.docker.com/get-docker/) installed on your system.
You might need to run the following commands with `sudo` depending on your system.
!!!

#### Docker Compose (Recommended)

- Start the container

```sh
docker-compose up -d # detached mode
```

- Stop the container

```sh
docker-compose stop # stops the container
docker-compose down # stops and removes the container
```

---

#### Docker

- Start Docker daemon (Skip if already running)

```sh
sudo dockerd
```

- Build the image

```sh
docker build -t jiosaavn .
```

- Run the image

```sh
docker run -p 80:3000 jiosaavn
```

- Open http://localhost to view it in the browser.

- Stop the container

```sh
docker ps
```

```sh
docker stop <container-id>
```

+++ Rust
:::content-center

### One Click Deploy

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/sumitkolhe/jiosaavn-api)
[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy)

:::content-center
Login to your [Render](https://render.com/) account and create a new [:globe_with_meridians: Web Service](https://dashboard.render.com/select-repo?type=web).

Fill in the details, choose `Runtime` as `Rust` and click on **Create Web Service**.

:::

---

:::content-center

### Build and Run Docker Image

:::

!!!warning Warning
You need to have [Docker](https://docs.docker.com/get-docker/) installed on your system.
You might need to run the following commands with `sudo` depending on your system.
!!!

#### Docker Compose (Recommended)

- Start the container

```sh
docker-compose up -d # detached mode
```

- Stop the container

```sh
docker-compose stop # stops the container
docker-compose down # stops and removes the container
```

---

#### Docker

- Start Docker daemon (Skip if already running)

```sh
sudo dockerd
```

- Build the image

```sh
docker build -t jiosaavn .
```

- Run the image

```sh
docker run -p 8080:8080 jiosaavn
```

- Stop the container

```sh
docker ps
```

```sh
docker stop <container-id>
```

---

#### [Shuttle.rs](https://shuttle.rs/)

- Install the [Shuttle CLI](https://github.com/shuttle-hq/shuttle/releases)

```sh
cargo install cargo-shuttle
```

- Add the following crates for shuttle to work

```sh
cargo add shuttle-runtime shuttle-axum
```

- Make sure to change the `main.rs` file to the following:

```rust #3-4,7,18 main.rs
// #[tokio::main]
// async fn main() {
#[shuttle_runtime::main]
async fn axum() -> shuttle_axum::ShuttleAxum {
    // tracing_subscriber::fmt::init();

    ...

    // let addr = "[::]:8080".parse().unwrap();

    // tracing::debug!("🚀 Server listening on {}", addr);
    // axum::Server::bind(&addr)
    //     .serve(app.into_make_service())
    //     .await
    //     .unwrap();

    Ok(router.into())
}
```

```sh
cargo shuttle project start
cargo shuttle deploy --allow-dirty
```

---

#### [Fly.io](https://fly.io/)

- Install the [Fly CLI](https://fly.io/docs/hands-on/install-flyctl)

```sh
curl -L https://fly.io/install.sh | sh
```

- A `fly.toml` file will be automatically generated by `fly launch` command which will ask a few questions to set everything up.

```sh
fly launch --name jiosaavn
```

- Deploy the app

```sh
fly deploy
```

+++

<div align=center>

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/rajput-hemant/jiosaavn-api-docs/blob/master/LICENSE) file for details.

## 🦾 Contributors:

[![](https://contrib.rocks/image?repo=rajput-hemant/jiosaavn-api-docs&max=500)](https://github.com/rajput-hemant/jiosaavn-api-docs/graphs/contributors)

</div>
