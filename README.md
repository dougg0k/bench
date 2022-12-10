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
| Bun                                                                                  | 69957.56 | 10015.89 | 91349.46  | 100%     |
| Hono                                                                                 | 55940.03 | 13407.54 | 69910.49  | 80%      |
| Deno                                                                                 | 53782.81 | 13303.41 | 75333.12  | 77%      |
| Megalo                                                                               | 53277.33 | 15399.34 | 70721.33  | 76%      |
| Fast                                                                                 | 51514.19 | 10499.64 | 59172.88  | 74%      |
| Hyper Express                                                                        | 51044.39 | 16396.24 | 63817.35  | 73%      |
| http                                                                                 | 48667.80 | 10466.70 | 56785.37  | 70%      |
| Reno                                                                                 | 42495.67 | 10713.05 | 54248.13  | 61%      |
| Node                                                                                 | 41883.63 | 9811.51  | 47423.79  | 60%      |
| Alosaur                                                                              | 39527.66 | 8053.94  | 45776.29  | 57%      |
| Router                                                                               | 34869.86 | 4393.61  | 38466.25  | 50%      |
| Fastify                                                                              | 34273.83 | 11450.65 | 41926.91  | 49%      |
| Little                                                                               | 30944.99 | 5816.84  | 36066.54  | 44%      |
| Oak                                                                                  | 28275.53 | 4771.71  | 32908.94  | 40%      |
| Aqua                                                                                 | 27606.88 | 3873.78  | 31095.20  | 39%      |
| Dinatra                                                                              | 23191.42 | 4333.69  | 29108.28  | 33%      |
| Abc                                                                                  | 18635.63 | 4714.89  | 24455.54  | 27%      |
| Opine                                                                                | 11666.03 | 3330.84  | 102360.77 | 17%      |
| Express                                                                              | 8288.21  | 1528.08  | 10932.61  | 12%      |
| Servest                                                                              | 6752.41  | 1835.07  | 9831.01   | 10%      |
| Acorn                                                                                | 4310.25  | 2932.04  | 17040.22  | 6%       |
| ![Chart](https://quickchart.io/chart/render/sf-7a828772-ebe7-44af-bff3-0946fd8949cf) |          |          |           |          |

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
| 18635.63 | 4714.89 | 24455.54 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 10902.86 | 14350.26 | 20611.77 | 22149.61 | 23110.69 | 23943.84 | 24278.27 |
| **Latency** | 2ms      | 2ms      | 2ms      | 2ms      | 4ms      | 4ms      | 5ms      |

### [Acorn](#acorn)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 4310.25  | 2932.04 | 17040.22 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90      | 95       | 99       |
| ----------- | ------- | ------- | ------- | ------- | ------- | -------- | -------- |
| **Req/Sec** | 2292.50 | 2800.52 | 3314.36 | 4381.21 | 9082.44 | 11965.48 | 14837.84 |
| **Latency** | 3ms     | 4ms     | 11ms    | 15ms    | 20ms    | 21ms     | 24ms     |

### [Alosaur](#alosaur)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 39527.66 | 8053.94 | 45776.29 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 29957.84 | 37404.52 | 43520.92 | 44035.48 | 44443.60 | 44844.44 | 45316.95 |
| **Latency** | 973µs    | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 3ms      |

### [Aqua](#aqua)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 27606.88 | 3873.78 | 31095.20 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 25403.08 | 26451.08 | 29302.74 | 29627.12 | 29872.00 | 30239.80 | 30747.34 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 2ms      | 3ms      |

### [Bun](#bun)

| **Stat** | Mean     | Stddev   | Max |
| -------- | -------- | -------- | --- |
| 69957.56 | 10015.89 | 91349.46 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 58190.51 | 60732.88 | 67540.62 | 80297.97 | 82009.76 | 83030.78 | 86628.88 |
| **Latency** | 444µs    | 559µs    | 674µs    | 791µs    | 1ms      | 1ms      | 1ms      |

### [Deno](#deno)

| **Stat** | Mean     | Stddev   | Max |
| -------- | -------- | -------- | --- |
| 53782.81 | 13303.41 | 75333.12 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 37400.43 | 47668.82 | 51922.98 | 67724.48 | 71484.69 | 72034.68 | 72724.79 |
| **Latency** | 554µs    | 697µs    | 794µs    | 1ms      | 1ms      | 1ms      | 2ms      |

### [Dinatra](#dinatra)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 23191.42 | 4333.69 | 29108.28 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 19971.33 | 20978.25 | 25461.99 | 25843.46 | 26114.36 | 26237.83 | 27154.77 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 3ms      | 5ms      |

### [Express](#express)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 8288.21  | 1528.08 | 10932.61 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90      | 95      | 99      |
| ----------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- |
| **Req/Sec** | 6130.70 | 7986.92 | 9047.16 | 9153.29 | 9240.30 | 9267.49 | 9301.79 |
| **Latency** | 5ms     | 5ms     | 5ms     | 5ms     | 7ms     | 8ms     | 13ms    |

### [Fast](#fast)

| **Stat** | Mean     | Stddev   | Max |
| -------- | -------- | -------- | --- |
| 51514.19 | 10499.64 | 59172.88 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 36262.51 | 48923.85 | 56927.41 | 57581.47 | 58002.41 | 58264.76 | 58602.69 |
| **Latency** | 769µs    | 815µs    | 896µs    | 940µs    | 992µs    | 1ms      | 3ms      |

### [Fastify](#fastify)

| **Stat** | Mean     | Stddev   | Max |
| -------- | -------- | -------- | --- |
| 34273.83 | 11450.65 | 41926.91 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 15449.00 | 38033.18 | 40397.43 | 41006.22 | 41317.84 | 41511.69 | 41727.62 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 3ms      | 4ms      |

### [Hono](#hono)

| **Stat** | Mean     | Stddev   | Max |
| -------- | -------- | -------- | --- |
| 55940.03 | 13407.54 | 69910.49 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 34305.20 | 48705.65 | 63513.52 | 65802.09 | 66510.75 | 66808.04 | 67300.48 |
| **Latency** | 680µs    | 714µs    | 778µs    | 844µs    | 1ms      | 1ms      | 3ms      |

### [http](#http)

| **Stat** | Mean     | Stddev   | Max |
| -------- | -------- | -------- | --- |
| 48667.80 | 10466.70 | 56785.37 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 29138.82 | 46172.50 | 54122.66 | 54628.43 | 55026.50 | 55272.16 | 55720.15 |
| **Latency** | 805µs    | 852µs    | 952µs    | 997µs    | 1ms      | 1ms      | 3ms      |

### [Hyper Express](#hyper-express)

| **Stat** | Mean     | Stddev   | Max |
| -------- | -------- | -------- | --- |
| 51044.39 | 16396.24 | 63817.35 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 25241.95 | 26368.60 | 62000.12 | 62557.67 | 62800.75 | 62908.29 | 63065.70 |
| **Latency** | 763µs    | 773µs    | 781µs    | 798µs    | 1ms      | 1ms      | 2ms      |

### [Little](#little)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 30944.99 | 5816.84 | 36066.54 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 20793.62 | 30280.59 | 33488.80 | 34515.94 | 35027.97 | 35374.60 | 35840.10 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 2ms      | 3ms      |

### [Megalo](#megalo)

| **Stat** | Mean     | Stddev   | Max |
| -------- | -------- | -------- | --- |
| 53277.33 | 15399.34 | 70721.33 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 27885.65 | 44778.14 | 63100.10 | 65090.65 | 65869.51 | 66318.68 | 67110.17 |
| **Latency** | 688µs    | 731µs    | 778µs    | 848µs    | 1ms      | 2ms      | 3ms      |

### [Node](#node)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 41883.63 | 9811.51 | 47423.79 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 20061.82 | 44811.20 | 45634.24 | 46325.94 | 46769.29 | 46917.43 | 47125.05 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 3ms      |

### [Oak](#oak)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 28275.53 | 4771.71 | 32908.94 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 21243.58 | 26714.48 | 30367.84 | 30763.84 | 31404.13 | 31763.82 | 32171.19 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 2ms      | 3ms      |

### [Opine](#opine)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 11666.03 | 3330.84 | 102360.77 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 10616.79 | 11144.47 | 11919.34 | 12093.76 | 12701.40 | 13238.01 | 13870.28 |
| **Latency** | 3ms      | 3ms      | 4ms      | 4ms      | 5ms      | 5ms      | 7ms      |

### [Reno](#reno)

| **Stat** | Mean     | Stddev   | Max |
| -------- | -------- | -------- | --- |
| 42495.67 | 10713.05 | 54248.13 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 25743.81 | 33652.16 | 48812.38 | 50635.78 | 51506.97 | 51843.81 | 52551.96 |
| **Latency** | 781µs    | 951µs    | 1ms      | 1ms      | 1ms      | 2ms      | 4ms      |

### [Router](#router)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 34869.86 | 4393.61 | 38466.25 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 31263.55 | 33919.05 | 36729.80 | 37053.02 | 37337.46 | 37603.55 | 38019.82 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      |

### [Servest](#servest)

| **Stat** | Mean    | Stddev  | Max |
| -------- | ------- | ------- | --- |
| 6752.41  | 1835.07 | 9831.01 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90      | 95      | 99      |
| ----------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- |
| **Req/Sec** | 4632.67 | 6214.74 | 7415.29 | 7914.08 | 8200.59 | 8375.78 | 9008.13 |
| **Latency** | 6ms     | 6ms     | 6ms     | 7ms     | 10ms    | 12ms    | 18ms    |

---

<p align="center">Generated 2022-12-10T01:21:18.254Z</p>
