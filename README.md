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
| Bun                                                                                  | 61669.11 | 9805.45  | 81035.69  | 100%     |
| Hyper Express                                                                        | 54724.92 | 11093.07 | 60862.16  | 89%      |
| Hono                                                                                 | 53857.62 | 9843.50  | 61468.92  | 87%      |
| Deno                                                                                 | 49344.61 | 12547.69 | 67763.79  | 80%      |
| Megalo                                                                               | 49152.21 | 12307.77 | 63833.91  | 80%      |
| Fast                                                                                 | 46219.64 | 10301.95 | 55099.25  | 75%      |
| http                                                                                 | 44724.11 | 9883.31  | 52425.23  | 73%      |
| Reno                                                                                 | 41252.64 | 10167.01 | 56613.78  | 67%      |
| Alosaur                                                                              | 35031.34 | 8042.71  | 42066.67  | 57%      |
| Node                                                                                 | 34112.45 | 10756.87 | 42247.07  | 55%      |
| Fastify                                                                              | 33962.48 | 5771.91  | 36905.58  | 55%      |
| Router                                                                               | 31663.23 | 4546.95  | 35585.07  | 51%      |
| Little                                                                               | 28738.64 | 4886.01  | 34477.36  | 47%      |
| Oak                                                                                  | 25791.73 | 3768.86  | 32858.42  | 42%      |
| Aqua                                                                                 | 24579.67 | 4137.23  | 29416.02  | 40%      |
| Dinatra                                                                              | 19916.19 | 4162.32  | 25927.38  | 32%      |
| Abc                                                                                  | 17441.53 | 3060.15  | 21740.29  | 28%      |
| Opine                                                                                | 9943.11  | 1568.00  | 15881.25  | 16%      |
| Express                                                                              | 6248.46  | 1738.42  | 9116.05   | 10%      |
| Servest                                                                              | 5996.89  | 4716.75  | 147953.46 | 10%      |
| Acorn                                                                                | 5153.52  | 5569.01  | 42711.77  | 8%       |
| ![Chart](https://quickchart.io/chart/render/sf-1469303f-7ad4-46f4-b483-dfe776280588) |          |          |           |          |

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
| 17441.53 | 3060.15 | 21740.29 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 15234.63 | 16716.36 | 18108.13 | 18992.41 | 20406.28 | 20677.23 | 21118.65 |
| **Latency** | 2ms      | 2ms      | 2ms      | 2ms      | 3ms      | 4ms      | 6ms      |

### [Acorn](#acorn)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 5153.52  | 5569.01 | 42711.77 |     |

| **Stat**    | 10     | 25      | 50      | 75      | 90       | 95       | 99       |
| ----------- | ------ | ------- | ------- | ------- | -------- | -------- | -------- |
| **Req/Sec** | 301.62 | 2420.51 | 3336.47 | 5147.45 | 11502.26 | 22608.90 | 24984.18 |
| **Latency** | 4ms    | 5ms     | 13ms    | 18ms    | 21ms     | 22ms     | 25ms     |

### [Alosaur](#alosaur)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 35031.34 | 8042.71 | 42066.67 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 24425.43 | 35087.77 | 38913.67 | 39623.83 | 40110.91 | 40330.83 | 40848.65 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 4ms      |

### [Aqua](#aqua)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 24579.67 | 4137.23 | 29416.02 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 18022.01 | 23411.54 | 26604.02 | 27395.08 | 27597.31 | 27814.22 | 28476.63 |
| **Latency** | 1ms      | 1ms      | 1ms      | 2ms      | 2ms      | 3ms      | 4ms      |

### [Bun](#bun)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 61669.11 | 9805.45 | 81035.69 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 52259.07 | 54969.84 | 58734.83 | 71807.93 | 73622.41 | 74770.74 | 77660.01 |
| **Latency** | 490µs    | 619µs    | 758µs    | 907µs    | 1ms      | 1ms      | 1ms      |

### [Deno](#deno)

| **Stat** | Mean     | Stddev   | Max |
| -------- | -------- | -------- | --- |
| 49344.61 | 12547.69 | 67763.79 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 32416.89 | 41511.66 | 51334.15 | 61014.79 | 62460.15 | 63167.13 | 64339.07 |
| **Latency** | 611µs    | 771µs    | 898µs    | 1ms      | 1ms      | 1ms      | 2ms      |

### [Dinatra](#dinatra)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 19916.19 | 4162.32 | 25927.38 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 15317.04 | 18123.40 | 21768.09 | 22452.36 | 23315.42 | 23800.91 | 24350.68 |
| **Latency** | 2ms      | 2ms      | 2ms      | 2ms      | 2ms      | 4ms      | 6ms      |

### [Express](#express)

| **Stat** | Mean    | Stddev  | Max |
| -------- | ------- | ------- | --- |
| 6248.46  | 1738.42 | 9116.05 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90      | 95      | 99      |
| ----------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- |
| **Req/Sec** | 4009.87 | 4564.09 | 7385.38 | 7674.84 | 7786.28 | 7837.16 | 7909.02 |
| **Latency** | 6ms     | 6ms     | 6ms     | 9ms     | 11ms    | 13ms    | 17ms    |

### [Fast](#fast)

| **Stat** | Mean     | Stddev   | Max |
| -------- | -------- | -------- | --- |
| 46219.64 | 10301.95 | 55099.25 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 32451.63 | 45335.41 | 51418.06 | 52013.58 | 52373.98 | 52598.95 | 53235.07 |
| **Latency** | 847µs    | 902µs    | 993µs    | 1ms      | 1ms      | 1ms      | 4ms      |

### [Fastify](#fastify)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 33962.48 | 5771.91 | 36905.58 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 33372.79 | 34751.13 | 35478.81 | 35977.39 | 36264.59 | 36452.17 | 36774.33 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 3ms      |

### [Hono](#hono)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 53857.62 | 9843.50 | 61468.92 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 41590.17 | 54309.73 | 58108.81 | 59148.00 | 59766.85 | 60125.35 | 60641.29 |
| **Latency** | 645µs    | 776µs    | 904µs    | 960µs    | 1ms      | 1ms      | 2ms      |

### [http](#http)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 44724.11 | 9883.31 | 52425.23 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 30683.87 | 42836.27 | 49820.98 | 50417.27 | 50771.30 | 51004.71 | 51414.79 |
| **Latency** | 875µs    | 934µs    | 1ms      | 1ms      | 1ms      | 1ms      | 4ms      |

### [Hyper Express](#hyper-express)

| **Stat** | Mean     | Stddev   | Max |
| -------- | -------- | -------- | --- |
| 54724.92 | 11093.07 | 60862.16 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 32017.66 | 58416.45 | 59271.22 | 59765.84 | 60005.71 | 60123.54 | 60317.59 |
| **Latency** | 773µs    | 782µs    | 796µs    | 813µs    | 1ms      | 1ms      | 2ms      |

### [Little](#little)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 28738.64 | 4886.01 | 34477.36 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 24679.90 | 27184.35 | 30939.39 | 31516.19 | 31822.17 | 32162.07 | 32620.92 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 3ms      |

### [Megalo](#megalo)

| **Stat** | Mean     | Stddev   | Max |
| -------- | -------- | -------- | --- |
| 49152.21 | 12307.77 | 63833.91 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 29643.02 | 43072.35 | 55583.04 | 57784.31 | 58501.83 | 58899.29 | 59698.26 |
| **Latency** | 764µs    | 820µs    | 876µs    | 952µs    | 1ms      | 1ms      | 4ms      |

### [Node](#node)

| **Stat** | Mean     | Stddev   | Max |
| -------- | -------- | -------- | --- |
| 34112.45 | 10756.87 | 42247.07 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 13438.32 | 35373.62 | 39601.24 | 40616.30 | 41185.30 | 41512.98 | 41911.96 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 3ms      | 4ms      |

### [Oak](#oak)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 25791.73 | 3768.86 | 32858.42 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 22231.45 | 25955.80 | 27116.84 | 27585.97 | 28132.17 | 28472.67 | 28844.30 |
| **Latency** | 1ms      | 1ms      | 1ms      | 2ms      | 2ms      | 2ms      | 3ms      |

### [Opine](#opine)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 9943.11  | 1568.00 | 15881.25 |     |

| **Stat**    | 10      | 25      | 50       | 75       | 90       | 95       | 99       |
| ----------- | ------- | ------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 8451.64 | 9436.16 | 10208.79 | 10519.39 | 11431.94 | 12185.83 | 13324.33 |
| **Latency** | 3ms     | 4ms     | 5ms      | 5ms      | 5ms      | 6ms      | 8ms      |

### [Reno](#reno)

| **Stat** | Mean     | Stddev   | Max |
| -------- | -------- | -------- | --- |
| 41252.64 | 10167.01 | 56613.78 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 24630.33 | 41700.56 | 46171.34 | 47155.92 | 47809.08 | 48148.41 | 48688.29 |
| **Latency** | 966µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 4ms      |

### [Router](#router)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 31663.23 | 4546.95 | 35585.07 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 26971.84 | 31218.82 | 33453.91 | 34053.88 | 34670.99 | 34867.36 | 35155.71 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 3ms      |

### [Servest](#servest)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 5996.89  | 4716.75 | 147953.46 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90      | 95      | 99      |
| ----------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- |
| **Req/Sec** | 3407.88 | 5710.45 | 6426.81 | 6827.94 | 7162.27 | 7248.65 | 8344.01 |
| **Latency** | 7ms     | 7ms     | 7ms     | 8ms     | 11ms    | 13ms    | 20ms    |

---

<p align="center">Generated 2022-11-28T01:28:19.462Z</p>
