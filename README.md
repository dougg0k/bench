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

| Framework                                                                            | Mean     | Stddev  | Max       | Relative |
| ------------------------------------------------------------------------------------ | -------- | ------- | --------- | -------- |
| Bun                                                                                  | 42319.58 | 7774.74 | 59194.89  | 100%     |
| Hyper Express                                                                        | 32650.07 | 7535.08 | 40237.96  | 77%      |
| Fast                                                                                 | 31969.28 | 7474.87 | 40366.88  | 76%      |
| http                                                                                 | 31008.44 | 7720.81 | 38539.78  | 73%      |
| Deno                                                                                 | 30847.41 | 8295.72 | 48212.20  | 73%      |
| Megalo                                                                               | 29135.26 | 8338.98 | 43214.83  | 69%      |
| Reno                                                                                 | 26331.30 | 6904.61 | 37455.72  | 62%      |
| Alosaur                                                                              | 23935.87 | 5444.23 | 29874.26  | 57%      |
| Router                                                                               | 21623.09 | 4091.99 | 28313.21  | 51%      |
| Hono                                                                                 | 21191.00 | 6780.13 | 38164.21  | 50%      |
| Little                                                                               | 18760.76 | 3702.14 | 25192.42  | 44%      |
| Node                                                                                 | 18683.73 | 4237.64 | 29712.58  | 44%      |
| Aqua                                                                                 | 17762.60 | 3452.00 | 24774.32  | 42%      |
| Fastify                                                                              | 15481.89 | 3025.64 | 34597.40  | 37%      |
| Oak                                                                                  | 15111.68 | 2858.72 | 25252.37  | 36%      |
| Dinatra                                                                              | 11963.46 | 2636.74 | 20928.16  | 28%      |
| Abc                                                                                  | 9571.15  | 2078.20 | 12858.52  | 23%      |
| Opine                                                                                | 6539.24  | 2345.82 | 72678.19  | 15%      |
| Servest                                                                              | 4004.37  | 3266.72 | 102827.10 | 9%       |
| Express                                                                              | 3986.11  | 1056.21 | 12638.55  | 9%       |
| Acorn                                                                                | 3926.22  | 3806.38 | 58777.20  | 9%       |
| ![Chart](https://quickchart.io/chart/render/sf-d2eb59aa-9f8e-489f-b548-b31b410895df) |          |         |           |          |

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
| 9571.15  | 2078.20 | 12858.52 |     |

| **Stat**    | 10      | 25      | 50       | 75       | 90       | 95       | 99       |
| ----------- | ------- | ------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 5852.77 | 8738.56 | 10480.02 | 10965.94 | 11305.01 | 11490.14 | 11926.40 |
| **Latency** | 4ms     | 4ms     | 4ms      | 5ms      | 6ms      | 8ms      | 11ms     |

### [Acorn](#acorn)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 3926.22  | 3806.38 | 58777.20 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90      | 95      | 99       |
| ----------- | ------- | ------- | ------- | ------- | ------- | ------- | -------- |
| **Req/Sec** | 1573.34 | 2420.78 | 3086.20 | 5346.72 | 7217.32 | 8225.49 | 10426.93 |
| **Latency** | 5ms     | 7ms     | 13ms    | 19ms    | 24ms    | 25ms    | 27ms     |

### [Alosaur](#alosaur)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 23935.87 | 5444.23 | 29874.26 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 15008.15 | 24035.62 | 26030.28 | 26997.44 | 27624.98 | 28026.26 | 29002.13 |
| **Latency** | 1ms      | 1ms      | 1ms      | 2ms      | 2ms      | 3ms      | 6ms      |

### [Aqua](#aqua)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 17762.60 | 3452.00 | 24774.32 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 12763.42 | 16509.79 | 18982.68 | 19906.14 | 20705.08 | 21055.17 | 21719.37 |
| **Latency** | 2ms      | 2ms      | 2ms      | 2ms      | 3ms      | 4ms      | 6ms      |

### [Bun](#bun)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 42319.58 | 7774.74 | 59194.89 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 33308.76 | 37266.82 | 41354.79 | 49202.12 | 52768.76 | 54139.30 | 56424.17 |
| **Latency** | 680µs    | 857µs    | 1ms      | 1ms      | 1ms      | 2ms      | 2ms      |

### [Deno](#deno)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 30847.41 | 8295.72 | 48212.20 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 20981.98 | 26427.09 | 30206.74 | 37023.68 | 42504.81 | 43721.55 | 44725.09 |
| **Latency** | 940µs    | 1ms      | 1ms      | 1ms      | 2ms      | 2ms      | 4ms      |

### [Dinatra](#dinatra)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 11963.46 | 2636.74 | 20928.16 |     |

| **Stat**    | 10      | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | ------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 9007.40 | 10886.18 | 12509.03 | 13696.86 | 14686.16 | 15089.99 | 15729.08 |
| **Latency** | 3ms     | 3ms      | 3ms      | 4ms      | 5ms      | 6ms      | 10ms     |

### [Express](#express)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 3986.11  | 1056.21 | 12638.55 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90      | 95      | 99      |
| ----------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- |
| **Req/Sec** | 2455.30 | 3756.55 | 4337.58 | 4525.90 | 4634.68 | 4686.19 | 4950.86 |
| **Latency** | 10ms    | 11ms    | 11ms    | 12ms    | 16ms    | 19ms    | 26ms    |

### [Fast](#fast)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 31969.28 | 7474.87 | 40366.88 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 20702.96 | 31402.86 | 35233.58 | 36444.94 | 37182.69 | 37734.07 | 38509.46 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 5ms      |

### [Fastify](#fastify)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 15481.89 | 3025.64 | 34597.40 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 13319.65 | 15419.33 | 16299.97 | 16892.29 | 17455.57 | 17814.67 | 18326.45 |
| **Latency** | 2ms      | 2ms      | 2ms      | 3ms      | 3ms      | 4ms      | 8ms      |

### [Hono](#hono)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 21191.00 | 6780.13 | 38164.21 |     |

| **Stat**    | 10      | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | ------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 9551.42 | 16688.17 | 23240.64 | 26203.63 | 27813.22 | 29167.47 | 31145.53 |
| **Latency** | 1ms     | 1ms      | 2ms      | 2ms      | 3ms      | 5ms      | 6ms      |

### [http](#http)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 31008.44 | 7720.81 | 38539.78 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 18883.56 | 29317.86 | 34507.41 | 35724.34 | 36566.42 | 37040.67 | 37997.26 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 5ms      |

### [Hyper Express](#hyper-express)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 32650.07 | 7535.08 | 40237.96 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 17346.89 | 33523.24 | 35727.99 | 36905.29 | 37631.73 | 38083.53 | 38909.86 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 3ms      | 4ms      |

### [Little](#little)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 18760.76 | 3702.14 | 25192.42 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 13304.04 | 17402.52 | 20124.82 | 21070.01 | 21792.68 | 22285.71 | 23119.14 |
| **Latency** | 1ms      | 2ms      | 2ms      | 2ms      | 3ms      | 4ms      | 6ms      |

### [Megalo](#megalo)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 29135.26 | 8338.98 | 43214.83 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 16010.78 | 26587.47 | 31610.22 | 34878.74 | 37122.25 | 38248.36 | 40374.82 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 2ms      | 6ms      |

### [Node](#node)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 18683.73 | 4237.64 | 29712.58 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 10478.40 | 19113.02 | 20116.36 | 20860.70 | 21340.83 | 21630.07 | 22086.43 |
| **Latency** | 2ms      | 2ms      | 2ms      | 2ms      | 2ms      | 4ms      | 7ms      |

### [Oak](#oak)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 15111.68 | 2858.72 | 25252.37 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 11404.83 | 14630.92 | 16110.37 | 16749.97 | 17306.46 | 17634.48 | 18345.49 |
| **Latency** | 2ms      | 2ms      | 3ms      | 3ms      | 3ms      | 5ms      | 7ms      |

### [Opine](#opine)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 6539.24  | 2345.82 | 72678.19 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90      | 95      | 99      |
| ----------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- |
| **Req/Sec** | 5611.15 | 6157.45 | 6655.46 | 6953.72 | 7201.60 | 7651.15 | 8754.65 |
| **Latency** | 5ms     | 7ms     | 7ms     | 8ms     | 9ms     | 10ms    | 14ms    |

### [Reno](#reno)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 26331.30 | 6904.61 | 37455.72 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 14219.39 | 25309.70 | 29211.47 | 30672.74 | 31619.58 | 32296.03 | 33192.85 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 3ms      | 6ms      |

### [Router](#router)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 21623.09 | 4091.99 | 28313.21 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 15890.39 | 20686.95 | 23220.73 | 24007.70 | 24782.73 | 25147.12 | 25966.11 |
| **Latency** | 1ms      | 1ms      | 2ms      | 2ms      | 2ms      | 3ms      | 5ms      |

### [Servest](#servest)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 4004.37  | 3266.72 | 102827.10 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90      | 95      | 99      |
| ----------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- |
| **Req/Sec** | 2099.41 | 3718.75 | 4255.68 | 4511.06 | 4893.37 | 5069.97 | 5535.02 |
| **Latency** | 10ms    | 11ms    | 11ms    | 13ms    | 17ms    | 21ms    | 30ms    |

---

<p align="center">Generated 2022-12-03T01:21:36.264Z</p>
