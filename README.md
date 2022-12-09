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
| Bun                                                                                  | 60760.76 | 9539.28  | 79010.43  | 100%     |
| Hyper Express                                                                        | 53370.79 | 11282.90 | 60880.47  | 88%      |
| Hono                                                                                 | 51322.89 | 9563.51  | 59107.71  | 84%      |
| Deno                                                                                 | 47390.84 | 11771.97 | 67500.82  | 78%      |
| Fast                                                                                 | 44603.82 | 10726.80 | 56116.23  | 73%      |
| http                                                                                 | 43519.40 | 9700.29  | 50740.63  | 72%      |
| Megalo                                                                               | 40774.46 | 11231.56 | 62130.59  | 67%      |
| Reno                                                                                 | 38940.26 | 10192.91 | 51428.13  | 64%      |
| Node                                                                                 | 36789.67 | 6303.66  | 40422.71  | 61%      |
| Alosaur                                                                              | 34355.08 | 8303.27  | 40738.72  | 57%      |
| Fastify                                                                              | 32075.94 | 5648.70  | 35414.83  | 53%      |
| Router                                                                               | 31112.42 | 4673.63  | 34796.44  | 51%      |
| Little                                                                               | 27947.89 | 4555.93  | 33213.37  | 46%      |
| Aqua                                                                                 | 25622.64 | 3450.64  | 29336.78  | 42%      |
| Oak                                                                                  | 25443.24 | 4128.61  | 31990.26  | 42%      |
| Dinatra                                                                              | 19212.45 | 4238.82  | 24127.87  | 32%      |
| Abc                                                                                  | 17489.08 | 2769.41  | 21721.99  | 29%      |
| Opine                                                                                | 10370.40 | 1420.15  | 15600.99  | 17%      |
| Express                                                                              | 6424.81  | 1666.27  | 9482.03   | 11%      |
| Servest                                                                              | 5985.20  | 5699.95  | 137298.20 | 10%      |
| Acorn                                                                                | 4412.58  | 3906.96  | 23607.71  | 7%       |
| ![Chart](https://quickchart.io/chart/render/sf-b28d7e8a-f694-4b7a-b1b0-0a9945d6b4d3) |          |          |           |          |

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
| 17489.08 | 2769.41 | 21721.99 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 14806.81 | 16325.96 | 18052.17 | 19007.76 | 20364.07 | 20513.70 | 20987.97 |
| **Latency** | 2ms      | 2ms      | 2ms      | 2ms      | 3ms      | 4ms      | 5ms      |

### [Acorn](#acorn)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 4412.58  | 3906.96 | 23607.71 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90      | 95       | 99       |
| ----------- | ------- | ------- | ------- | ------- | ------- | -------- | -------- |
| **Req/Sec** | 1988.50 | 2571.94 | 3113.20 | 4498.00 | 9546.97 | 12065.08 | 22191.32 |
| **Latency** | 4ms     | 5ms     | 12ms    | 17ms    | 20ms    | 23ms     | 26ms     |

### [Alosaur](#alosaur)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 34355.08 | 8303.27 | 40738.72 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 22675.73 | 35187.41 | 38280.38 | 38914.02 | 39424.08 | 39700.79 | 40091.77 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 5ms      |

### [Aqua](#aqua)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 25622.64 | 3450.64 | 29336.78 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 22477.09 | 23585.85 | 27290.52 | 27563.34 | 27840.82 | 28160.11 | 28671.98 |
| **Latency** | 1ms      | 1ms      | 1ms      | 2ms      | 2ms      | 3ms      | 3ms      |

### [Bun](#bun)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 60760.76 | 9539.28 | 79010.43 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 49842.88 | 52210.02 | 57831.23 | 71044.20 | 72743.64 | 73532.55 | 74887.38 |
| **Latency** | 499µs    | 629µs    | 761µs    | 908µs    | 1ms      | 1ms      | 1ms      |

### [Deno](#deno)

| **Stat** | Mean     | Stddev   | Max |
| -------- | -------- | -------- | --- |
| 47390.84 | 11771.97 | 67500.82 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 32626.63 | 40548.28 | 46668.83 | 58946.11 | 62116.91 | 62805.38 | 63959.16 |
| **Latency** | 627µs    | 798µs    | 915µs    | 1ms      | 1ms      | 1ms      | 3ms      |

### [Dinatra](#dinatra)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 19212.45 | 4238.82 | 24127.87 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 14790.33 | 15967.87 | 21489.92 | 21830.51 | 22346.26 | 22935.10 | 23329.17 |
| **Latency** | 2ms      | 2ms      | 2ms      | 2ms      | 3ms      | 4ms      | 6ms      |

### [Express](#express)

| **Stat** | Mean    | Stddev  | Max |
| -------- | ------- | ------- | --- |
| 6424.81  | 1666.27 | 9482.03 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90      | 95      | 99      |
| ----------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- |
| **Req/Sec** | 4135.99 | 4805.97 | 7438.32 | 7597.41 | 7700.32 | 7739.02 | 7787.39 |
| **Latency** | 6ms     | 6ms     | 6ms     | 7ms     | 11ms    | 12ms    | 17ms    |

### [Fast](#fast)

| **Stat** | Mean     | Stddev   | Max |
| -------- | -------- | -------- | --- |
| 44603.82 | 10726.80 | 56116.23 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 27567.90 | 39990.35 | 50413.19 | 51143.77 | 51525.13 | 51750.44 | 52250.41 |
| **Latency** | 862µs    | 925µs    | 1ms      | 1ms      | 1ms      | 1ms      | 4ms      |

### [Fastify](#fastify)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 32075.94 | 5648.70 | 35414.83 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 31680.22 | 32820.42 | 33703.72 | 34120.52 | 34369.50 | 34511.12 | 34778.68 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 4ms      |

### [Hono](#hono)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 51322.89 | 9563.51 | 59107.71 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 39771.13 | 48153.48 | 55633.98 | 57563.85 | 58136.07 | 58414.90 | 58927.86 |
| **Latency** | 782µs    | 834µs    | 877µs    | 958µs    | 1ms      | 1ms      | 2ms      |

### [http](#http)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 43519.40 | 9700.29 | 50740.63 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 29958.14 | 44745.99 | 48214.02 | 48704.90 | 49127.53 | 49413.38 | 49835.51 |
| **Latency** | 900µs    | 961µs    | 1ms      | 1ms      | 1ms      | 1ms      | 4ms      |

### [Hyper Express](#hyper-express)

| **Stat** | Mean     | Stddev   | Max |
| -------- | -------- | -------- | --- |
| 53370.79 | 11282.90 | 60880.47 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 29114.61 | 56464.35 | 58031.42 | 58828.91 | 59085.17 | 59220.23 | 59420.88 |
| **Latency** | 785µs    | 796µs    | 810µs    | 830µs    | 1ms      | 1ms      | 2ms      |

### [Little](#little)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 27947.89 | 4555.93 | 33213.37 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 23956.47 | 26090.31 | 29873.30 | 30619.94 | 31266.32 | 31564.34 | 31948.93 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 3ms      | 4ms      |

### [Megalo](#megalo)

| **Stat** | Mean     | Stddev   | Max |
| -------- | -------- | -------- | --- |
| 40774.46 | 11231.56 | 62130.59 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 23132.90 | 37353.83 | 42359.98 | 46059.23 | 55587.46 | 56449.24 | 57558.46 |
| **Latency** | 791µs    | 874µs    | 1ms      | 1ms      | 1ms      | 2ms      | 5ms      |

### [Node](#node)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 36789.67 | 6303.66 | 40422.71 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 35946.43 | 37604.95 | 38535.14 | 39114.67 | 39556.24 | 39774.85 | 40129.36 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 3ms      |

### [Oak](#oak)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 25443.24 | 4128.61 | 31990.26 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 21401.75 | 25725.25 | 26966.02 | 27423.25 | 28174.66 | 28431.84 | 28822.05 |
| **Latency** | 1ms      | 1ms      | 1ms      | 2ms      | 2ms      | 3ms      | 4ms      |

### [Opine](#opine)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 10370.40 | 1420.15 | 15600.99 |     |

| **Stat**    | 10      | 25      | 50       | 75       | 90       | 95       | 99       |
| ----------- | ------- | ------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 9125.89 | 9912.04 | 10769.20 | 10935.31 | 11190.32 | 11855.27 | 13130.17 |
| **Latency** | 3ms     | 4ms     | 4ms      | 5ms      | 5ms      | 6ms      | 8ms      |

### [Reno](#reno)

| **Stat** | Mean     | Stddev   | Max |
| -------- | -------- | -------- | --- |
| 38940.26 | 10192.91 | 51428.13 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 21290.53 | 36722.45 | 44233.10 | 45134.60 | 45722.17 | 46001.98 | 46651.69 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 5ms      |

### [Router](#router)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 31112.42 | 4673.63 | 34796.44 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 25741.52 | 30575.13 | 33273.66 | 33613.18 | 33909.32 | 34223.28 | 34618.07 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 3ms      |

### [Servest](#servest)

| **Stat** | Mean    | Stddev    | Max |
| -------- | ------- | --------- | --- |
| 5985.20  | 5699.95 | 137298.20 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90      | 95      | 99      |
| ----------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- |
| **Req/Sec** | 3002.20 | 5667.16 | 6347.49 | 6800.15 | 7106.41 | 7182.25 | 8192.79 |
| **Latency** | 7ms     | 7ms     | 7ms     | 8ms     | 12ms    | 14ms    | 22ms    |

---

<p align="center">Generated 2022-12-09T01:27:26.642Z</p>
