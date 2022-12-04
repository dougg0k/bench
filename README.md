<div align="center">
  <h1><code>bench</code></h1>
  <p>
    <strong>📊 Daily benchmarks of deno & node HTTP frameworks</strong>
  </p>
  <br>
  <p align="center">
    <a alt="Bench" href="https://github.com/denosaurs/bench/actions">
      <img src="https://img.shields.io/github/workflow/status/denosaurs/bench/bench" />
    </a>
  </p>
</div>

# Table of Contents

- [Overview](#overview)
  - [Hello, bench!](#hello-bench)
- [Frameworks](#frameworks)
  - [Abc](#abc)
  - [Acorn](#acorn)
  - [Alosaur](#alosaur)
  - [Aqua](#aqua)
  - [Bun](#bun)
  - [Deno](#deno)
  - [Dinatra](#dinatra)
  - [Express](#express)
  - [Fast](#fast)
  - [Fastify](#fastify)
  - [Hono](#hono)
  - [http](#http)
  - [Hyper Express](#hyper-express)
  - [Little](#little)
  - [Megalo](#megalo)
  - [Node](#node)
  - [Oak](#oak)
  - [Opine](#opine)
  - [Reno](#reno)
  - [Router](#router)
  - [Servest](#servest)
- [Benchmarks](#benchmarks)
  - [Hello, bench!](#hello-bench-1)
    - [Abc](#abc-1)
    - [Acorn](#acorn-1)
    - [Alosaur](#alosaur-1)
    - [Aqua](#aqua-1)
    - [Bun](#bun-1)
    - [Deno](#deno-1)
    - [Dinatra](#dinatra-1)
    - [Express](#express-1)
    - [Fast](#fast-1)
    - [Fastify](#fastify-1)
    - [Hono](#hono-1)
    - [http](#http-1)
    - [Hyper Express](#hyper-express-1)
    - [Little](#little-1)
    - [Megalo](#megalo-1)
    - [Node](#node-1)
    - [Oak](#oak-1)
    - [Opine](#opine-1)
    - [Reno](#reno-1)
    - [Router](#router-1)
    - [Servest](#servest-1)

# Overview

## Hello, bench!

| Framework                                                                            | Mean     | Stddev   | Max       | Relative |
| ------------------------------------------------------------------------------------ | -------- | -------- | --------- | -------- |
| Bun                                                                                  | 61670.06 | 8421.79  | 81332.97  | 100%     |
| Hono                                                                                 | 55248.67 | 9498.09  | 61621.90  | 90%      |
| Hyper Express                                                                        | 54785.80 | 11376.89 | 62600.96  | 89%      |
| Deno                                                                                 | 46433.51 | 11582.21 | 68309.91  | 75%      |
| Fast                                                                                 | 46099.65 | 10745.36 | 146478.79 | 75%      |
| Megalo                                                                               | 45581.67 | 15731.20 | 64837.06  | 74%      |
| http                                                                                 | 44898.04 | 9679.29  | 52022.65  | 73%      |
| Reno                                                                                 | 37841.14 | 11425.55 | 52513.71  | 61%      |
| Node                                                                                 | 37683.05 | 6491.42  | 41373.45  | 61%      |
| Alosaur                                                                              | 35215.86 | 7678.44  | 42104.60  | 57%      |
| Fastify                                                                              | 32305.27 | 5809.79  | 37654.06  | 52%      |
| Router                                                                               | 31828.52 | 4655.30  | 36025.08  | 52%      |
| Little                                                                               | 29305.88 | 4584.48  | 33672.64  | 48%      |
| Oak                                                                                  | 25862.14 | 3739.46  | 30002.46  | 42%      |
| Aqua                                                                                 | 24486.39 | 4755.21  | 30267.17  | 40%      |
| Dinatra                                                                              | 19827.13 | 3878.85  | 26329.26  | 32%      |
| Abc                                                                                  | 18275.95 | 2095.28  | 22228.24  | 30%      |
| Opine                                                                                | 10459.26 | 1460.96  | 18429.13  | 17%      |
| Express                                                                              | 6113.70  | 1967.57  | 34314.88  | 10%      |
| Servest                                                                              | 5906.01  | 1725.91  | 8550.02   | 10%      |
| Acorn                                                                                | 4411.70  | 4361.66  | 106722.45 | 7%       |
| ![Chart](https://quickchart.io/chart/render/sf-96de2978-4425-4bb5-8736-662552257562) |          |          |           |          |

# Frameworks

## [Abc](https://deno.land/x/abc)

A better Deno framework to create web application

## [Acorn](https://deno.land/x/acorn)

A focused RESTful server framework for Deno 🌰🦕

## [Alosaur](https://deno.land/x/alosaur)

Deno web framework with many decorators

## [Aqua](https://deno.land/x/aqua)

A minimal and fast 🏃 web framework for Deno

## [Bun](https://bun.sh/)

Bun is a fast all-in-one JavaScript runtime

## [Deno](https://deno.land/)

A modern runtime for JavaScript and TypeScript

## [Dinatra](https://github.com/syumai/dinatra)

Sinatra like light weight web app framework for deno.

## [Express](https://expressjs.com/)

Fast, unopinionated, minimalist web framework for Node.js

## [Fast](https://deno.land/x/fast)

Small web framework with near-native performance.

## [Fastify](https://www.fastify.io/)

Fast and low overhead web framework, for Node.js

## [Hono](https://github.com/honojs/hono)

Ultrafast web framework for Cloudflare Workers and Deno. Fast, but not only
fast.

## [http](https://deno.land/std/http)

The deno standard library http server

## [Hyper Express](https://github.com/kartikk221/hyper-express)

High performance Node.js webserver with a simple-to-use API powered by
uWebsockets.js under the hood.

## [Little](https://deno.land/x/little)

A minimalistic connect-like web framework. Automatically works out of the box
with Deno Deploy, Deno's Native HTTP and Deno's Standard HTTP server.

## [Megalo](https://github.com/tsar-boomba/megalo)

Deno HTTP server framework focused on speed

## [Node](https://nodejs.org/)

Node.js® is a JavaScript runtime built on Chrome's V8 JavaScript engine.

## [Oak](https://deno.land/x/oak)

A middleware framework for Deno's native HTTP server, Deno Deploy and Node.js
16.5 and later. It also includes a middleware router.

## [Opine](https://deno.land/x/opine)

Fast, minimalist web framework for Deno ported from ExpressJS.

## [Reno](https://deno.land/x/reno)

A thin, testable routing library designed to sit on top of Deno's standard HTTP
module.

## [Router](https://crux.land/router@0.0.12)

The tiny, modern and fast router by the denosaurs for deno and deno deploy. Used
by projects like fresh

## [Servest](https://servestjs.org/)

🌾A progressive http server for Deno🌾

# Benchmarks

## Hello, bench!

A simple benchmark which expects a response simply containing the text
"`Hello, Bench!`"

### [Abc](#abc)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 18275.95 | 2095.28 | 22228.24 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 16101.88 | 17440.23 | 18651.79 | 19407.50 | 20473.76 | 20889.12 | 21388.22 |
| **Latency** | 2ms      | 2ms      | 2ms      | 2ms      | 3ms      | 3ms      | 4ms      |

### [Acorn](#acorn)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 4411.70  | 4361.66 | 106722.45 |     |

| **Stat**    | 10    | 25      | 50      | 75      | 90      | 95       | 99       |
| ----------- | ----- | ------- | ------- | ------- | ------- | -------- | -------- |
| **Req/Sec** | 86.86 | 2475.19 | 3415.38 | 5681.74 | 9065.77 | 11394.84 | 13103.24 |
| **Latency** | 4ms   | 5ms     | 12ms    | 18ms    | 21ms    | 22ms     | 26ms     |

### [Alosaur](#alosaur)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 35215.86 | 7678.44 | 42104.60 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 24311.30 | 35954.11 | 38706.76 | 39405.31 | 39864.34 | 40075.53 | 40486.04 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 4ms      |

### [Aqua](#aqua)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 24486.39 | 4755.21 | 30267.17 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 17103.50 | 23302.21 | 26906.31 | 27773.68 | 28252.19 | 28710.15 | 29254.38 |
| **Latency** | 1ms      | 1ms      | 1ms      | 2ms      | 2ms      | 3ms      | 4ms      |

### [Bun](#bun)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 61670.06 | 8421.79 | 81332.97 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 53530.78 | 56160.20 | 58848.16 | 70425.00 | 72647.95 | 73624.70 | 77415.10 |
| **Latency** | 496µs    | 619µs    | 763µs    | 915µs    | 1ms      | 1ms      | 1ms      |

### [Deno](#deno)

| **Stat** | Mean     | Stddev   | Max |
| -------- | -------- | -------- | --- |
| 46433.51 | 11582.21 | 68309.91 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 32953.66 | 40720.51 | 45596.15 | 56236.84 | 61767.78 | 62635.40 | 63720.08 |
| **Latency** | 628µs    | 803µs    | 930µs    | 1ms      | 1ms      | 1ms      | 3ms      |

### [Dinatra](#dinatra)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 19827.13 | 3878.85 | 26329.26 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 15261.58 | 16724.59 | 21680.60 | 22133.27 | 22920.98 | 23388.64 | 24028.72 |
| **Latency** | 2ms      | 2ms      | 2ms      | 2ms      | 3ms      | 4ms      | 5ms      |

### [Express](#express)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 6113.70  | 1967.57 | 34314.88 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90      | 95      | 99      |
| ----------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- |
| **Req/Sec** | 3779.62 | 4542.55 | 7173.21 | 7574.12 | 7693.70 | 7725.77 | 7776.49 |
| **Latency** | 6ms     | 6ms     | 6ms     | 9ms     | 11ms    | 13ms    | 17ms    |

### [Fast](#fast)

| **Stat** | Mean     | Stddev    | Max |
| -------- | -------- | --------- | --- |
| 46099.65 | 10745.36 | 146478.79 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 31028.01 | 43616.38 | 51419.07 | 52013.30 | 52415.70 | 52640.45 | 52979.24 |
| **Latency** | 849µs    | 908µs    | 991µs    | 1ms      | 1ms      | 1ms      | 4ms      |

### [Fastify](#fastify)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 32305.27 | 5809.79 | 37654.06 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 31219.54 | 33210.80 | 33959.96 | 34427.40 | 34741.19 | 34942.82 | 35135.69 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 3ms      |

### [Hono](#hono)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 55248.67 | 9498.09 | 61621.90 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 47725.29 | 55752.71 | 58620.74 | 59760.09 | 60202.13 | 60489.69 | 60886.53 |
| **Latency** | 749µs    | 779µs    | 842µs    | 928µs    | 971µs    | 1ms      | 2ms      |

### [http](#http)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 44898.04 | 9679.29 | 52022.65 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 31502.55 | 46444.37 | 49608.62 | 50116.65 | 50482.05 | 50658.02 | 51047.85 |
| **Latency** | 875µs    | 936µs    | 1ms      | 1ms      | 1ms      | 1ms      | 4ms      |

### [Hyper Express](#hyper-express)

| **Stat** | Mean     | Stddev   | Max |
| -------- | -------- | -------- | --- |
| 54785.80 | 11376.89 | 62600.96 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 32102.74 | 58361.01 | 59511.50 | 60025.53 | 60276.27 | 60413.90 | 60659.77 |
| **Latency** | 767µs    | 778µs    | 792µs    | 810µs    | 1ms      | 1ms      | 2ms      |

### [Little](#little)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 29305.88 | 4584.48 | 33672.64 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 25161.13 | 27577.25 | 31249.87 | 31846.34 | 32490.29 | 32772.03 | 33129.99 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 3ms      |

### [Megalo](#megalo)

| **Stat** | Mean     | Stddev   | Max |
| -------- | -------- | -------- | --- |
| 45581.67 | 15731.20 | 64837.06 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 19551.33 | 34017.87 | 54573.96 | 58055.76 | 58921.52 | 59314.62 | 60915.35 |
| **Latency** | 763µs    | 819µs    | 875µs    | 956µs    | 1ms      | 2ms      | 4ms      |

### [Node](#node)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 37683.05 | 6491.42 | 41373.45 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 36800.66 | 38616.42 | 39374.63 | 39974.16 | 40445.11 | 40701.15 | 41105.45 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 3ms      |

### [Oak](#oak)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 25862.14 | 3739.46 | 30002.46 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 22169.70 | 26051.46 | 27200.41 | 27649.64 | 28382.17 | 28620.25 | 28969.45 |
| **Latency** | 1ms      | 1ms      | 1ms      | 2ms      | 2ms      | 2ms      | 3ms      |

### [Opine](#opine)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 10459.26 | 1460.96 | 18429.13 |     |

| **Stat**    | 10      | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | ------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 9252.97 | 10027.02 | 10843.91 | 11003.25 | 11348.60 | 11972.90 | 13261.52 |
| **Latency** | 3ms     | 4ms      | 4ms      | 5ms      | 5ms      | 5ms      | 7ms      |

### [Reno](#reno)

| **Stat** | Mean     | Stddev   | Max |
| -------- | -------- | -------- | --- |
| 37841.14 | 11425.55 | 52513.71 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 18203.74 | 29129.49 | 43407.84 | 46883.15 | 47925.66 | 48385.90 | 49220.16 |
| **Latency** | 950µs    | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 4ms      |

### [Router](#router)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 31828.52 | 4655.30 | 36025.08 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 27035.29 | 30919.33 | 33826.45 | 34360.14 | 34809.93 | 35054.57 | 35417.39 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 3ms      |

### [Servest](#servest)

| **Stat** | Mean    | Stddev  | Max |
| -------- | ------- | ------- | --- |
| 5906.01  | 1725.91 | 8550.02 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90      | 95      | 99      |
| ----------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- |
| **Req/Sec** | 3331.16 | 5795.07 | 6522.80 | 6913.93 | 7225.62 | 7321.90 | 8221.69 |
| **Latency** | 7ms     | 7ms     | 7ms     | 8ms     | 12ms    | 13ms    | 22ms    |

---

<p align="center">Generated 2022-12-04T01:26:58.323Z</p>
