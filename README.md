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

| Framework                                                                            | Mean     | Stddev   | Max      | Relative |
| ------------------------------------------------------------------------------------ | -------- | -------- | -------- | -------- |
| Bun                                                                                  | 41531.60 | 10594.79 | 61956.85 | 100%     |
| Hyper Express                                                                        | 32865.31 | 7994.03  | 39084.83 | 79%      |
| http                                                                                 | 30971.80 | 8936.81  | 44256.12 | 75%      |
| Fast                                                                                 | 30688.65 | 8608.05  | 42254.05 | 74%      |
| Deno                                                                                 | 28978.47 | 8944.54  | 51602.79 | 70%      |
| Megalo                                                                               | 27590.81 | 8162.78  | 45679.94 | 66%      |
| Reno                                                                                 | 26362.51 | 7560.98  | 36117.50 | 63%      |
| Alosaur                                                                              | 24663.31 | 6458.09  | 54602.18 | 59%      |
| Hono                                                                                 | 24098.03 | 7271.07  | 41802.54 | 58%      |
| Router                                                                               | 20389.00 | 4823.51  | 32241.29 | 49%      |
| Little                                                                               | 19304.92 | 3739.27  | 25893.75 | 46%      |
| Aqua                                                                                 | 18755.87 | 3752.65  | 25533.40 | 45%      |
| Oak                                                                                  | 15748.04 | 3074.94  | 20027.17 | 38%      |
| Node                                                                                 | 14747.86 | 2642.23  | 21868.03 | 36%      |
| Fastify                                                                              | 14205.97 | 2602.68  | 35622.38 | 34%      |
| Dinatra                                                                              | 12029.71 | 2709.19  | 23485.86 | 29%      |
| Abc                                                                                  | 10187.99 | 1663.14  | 12640.24 | 25%      |
| Opine                                                                                | 6182.72  | 1048.19  | 10890.99 | 15%      |
| Acorn                                                                                | 4472.82  | 3705.68  | 42216.36 | 11%      |
| Servest                                                                              | 3923.69  | 2916.87  | 90156.39 | 9%       |
| Express                                                                              | 3715.31  | 972.55   | 11444.85 | 9%       |
| ![Chart](https://quickchart.io/chart/render/sf-753fc539-ea66-4a39-bbf7-6fa86b6b621a) |          |          |          |          |

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
| 10187.99 | 1663.14 | 12640.24 |     |

| **Stat**    | 10      | 25      | 50       | 75       | 90       | 95       | 99       |
| ----------- | ------- | ------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 8239.24 | 9850.56 | 10780.16 | 11136.85 | 11555.93 | 11758.91 | 12049.76 |
| **Latency** | 4ms     | 4ms     | 4ms      | 4ms      | 5ms      | 6ms      | 10ms     |

### [Acorn](#acorn)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 4472.82  | 3705.68 | 42216.36 |     |

| **Stat**    | 10    | 25      | 50      | 75      | 90      | 95       | 99       |
| ----------- | ----- | ------- | ------- | ------- | ------- | -------- | -------- |
| **Req/Sec** | 91.77 | 2218.89 | 3392.27 | 6287.16 | 9514.43 | 12483.42 | 13180.65 |
| **Latency** | 6ms   | 7ms     | 12ms    | 20ms    | 24ms    | 25ms     | 29ms     |

### [Alosaur](#alosaur)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 24663.31 | 6458.09 | 54602.18 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 14814.07 | 23019.00 | 27612.80 | 28667.17 | 29190.25 | 29540.69 | 30105.15 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 3ms      | 6ms      |

### [Aqua](#aqua)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 18755.87 | 3752.65 | 25533.40 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 13087.94 | 17476.27 | 20271.05 | 21273.82 | 21864.24 | 22255.11 | 23086.77 |
| **Latency** | 1ms      | 2ms      | 2ms      | 2ms      | 3ms      | 4ms      | 6ms      |

### [Bun](#bun)

| **Stat** | Mean     | Stddev   | Max |
| -------- | -------- | -------- | --- |
| 41531.60 | 10594.79 | 61956.85 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 29587.26 | 33514.99 | 41212.36 | 50417.13 | 55826.76 | 57093.10 | 58608.75 |
| **Latency** | 663µs    | 830µs    | 1ms      | 1ms      | 1ms      | 2ms      | 3ms      |

### [Deno](#deno)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 28978.47 | 8944.54 | 51602.79 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 18175.42 | 24404.63 | 27910.14 | 33471.94 | 43573.19 | 45645.64 | 47090.43 |
| **Latency** | 957µs    | 1ms      | 1ms      | 2ms      | 2ms      | 3ms      | 5ms      |

### [Dinatra](#dinatra)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 12029.71 | 2709.19 | 23485.86 |     |

| **Stat**    | 10      | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | ------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 9143.89 | 11001.43 | 12665.99 | 13625.07 | 14689.71 | 15013.55 | 15467.27 |
| **Latency** | 3ms     | 3ms      | 3ms      | 3ms      | 5ms      | 6ms      | 10ms     |

### [Express](#express)

| **Stat** | Mean   | Stddev   | Max |
| -------- | ------ | -------- | --- |
| 3715.31  | 972.55 | 11444.85 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90      | 95      | 99      |
| ----------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- |
| **Req/Sec** | 2438.50 | 3130.49 | 4115.97 | 4361.10 | 4493.55 | 4559.64 | 4675.84 |
| **Latency** | 11ms    | 11ms    | 11ms    | 15ms    | 17ms    | 20ms    | 27ms    |

### [Fast](#fast)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 30688.65 | 8608.05 | 42254.05 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 17118.14 | 24467.76 | 34842.40 | 37377.49 | 38113.23 | 38440.01 | 39339.16 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 3ms      | 5ms      |

### [Fastify](#fastify)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 14205.97 | 2602.68 | 35622.38 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 12213.56 | 14370.85 | 14954.13 | 15315.16 | 15607.65 | 15759.73 | 16173.10 |
| **Latency** | 3ms      | 3ms      | 3ms      | 3ms      | 3ms      | 5ms      | 8ms      |

### [Hono](#hono)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 24098.03 | 7271.07 | 41802.54 |     |

| **Stat**    | 10      | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | ------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 9818.06 | 21496.52 | 27009.72 | 29331.99 | 30563.57 | 31343.56 | 32386.47 |
| **Latency** | 1ms     | 1ms      | 1ms      | 2ms      | 2ms      | 4ms      | 6ms      |

### [http](#http)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 30971.80 | 8936.81 | 44256.12 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 16519.64 | 26053.40 | 35440.75 | 37418.72 | 38208.78 | 38653.97 | 39611.69 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 2ms      | 5ms      |

### [Hyper Express](#hyper-express)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 32865.31 | 7994.03 | 39084.83 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 14950.41 | 34350.84 | 36321.80 | 37128.22 | 37716.17 | 38035.77 | 38639.42 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 3ms      | 4ms      |

### [Little](#little)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 19304.92 | 3739.27 | 25893.75 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 14902.98 | 17721.03 | 20778.70 | 21703.69 | 22275.74 | 22606.33 | 23313.16 |
| **Latency** | 1ms      | 2ms      | 2ms      | 2ms      | 3ms      | 4ms      | 6ms      |

### [Megalo](#megalo)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 27590.81 | 8162.78 | 45679.94 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 15594.82 | 24313.62 | 28309.49 | 32513.00 | 38117.41 | 40099.80 | 41865.90 |
| **Latency** | 1ms      | 1ms      | 1ms      | 2ms      | 2ms      | 3ms      | 6ms      |

### [Node](#node)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 14747.86 | 2642.23 | 21868.03 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 11841.63 | 14861.08 | 15472.26 | 16040.42 | 16532.24 | 16748.40 | 17011.28 |
| **Latency** | 2ms      | 2ms      | 3ms      | 3ms      | 3ms      | 4ms      | 8ms      |

### [Oak](#oak)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 15748.04 | 3074.94 | 20027.17 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 12019.44 | 14513.34 | 16879.00 | 17595.12 | 18169.64 | 18550.43 | 19197.26 |
| **Latency** | 2ms      | 2ms      | 2ms      | 3ms      | 3ms      | 5ms      | 7ms      |

### [Opine](#opine)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 6182.72  | 1048.19 | 10890.99 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90      | 95      | 99      |
| ----------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- |
| **Req/Sec** | 5037.60 | 5880.23 | 6448.67 | 6716.87 | 6946.99 | 7137.40 | 8359.84 |
| **Latency** | 5ms     | 7ms     | 8ms     | 8ms     | 9ms     | 11ms    | 14ms    |

### [Reno](#reno)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 26362.51 | 7560.98 | 36117.50 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 13762.12 | 24127.02 | 29710.70 | 31430.49 | 32612.07 | 33073.76 | 34409.23 |
| **Latency** | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 3ms      | 6ms      |

### [Router](#router)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 20389.00 | 4823.51 | 32241.29 |     |

| **Stat**    | 10       | 25       | 50       | 75       | 90       | 95       | 99       |
| ----------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec** | 13792.96 | 17437.23 | 22174.83 | 24103.12 | 24873.85 | 25338.70 | 26105.42 |
| **Latency** | 1ms      | 1ms      | 2ms      | 2ms      | 3ms      | 4ms      | 6ms      |

### [Servest](#servest)

| **Stat** | Mean    | Stddev   | Max |
| -------- | ------- | -------- | --- |
| 3923.69  | 2916.87 | 90156.39 |     |

| **Stat**    | 10      | 25      | 50      | 75      | 90      | 95      | 99      |
| ----------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- |
| **Req/Sec** | 1928.11 | 3714.19 | 4224.21 | 4435.71 | 4801.36 | 4987.59 | 5378.31 |
| **Latency** | 10ms    | 11ms    | 11ms    | 14ms    | 18ms    | 21ms    | 28ms    |

---

<p align="center">Generated 2022-12-12T01:26:51.965Z</p>
