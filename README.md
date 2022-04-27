# Awesome Go performance

Collection of the Awesome™ Go libraries, tools, project around performance.

## Contents

- [Algorithm](#algorithm)
- [Assembly](#assembly)
- [Benchmarks](#benchmarks)
- [Compiling](#compiling)
- [Concurrency](#concurrency)
- [Crypto](#crypto)
- [GC](#gc)
- [Hardware](#hardware)
- [Hash](#hash)
- [I/O](#io)
- [Math](#math)
- [Network](#network)
- [Profiling](#profiling)
- [Storage](#storage)
- [Testing](#testing)
- [Articles](#articles)
- [Other](#other)

## Algorithm

- [shawnsmithdev/zermelo](https://github.com/shawnsmithdev/zermelo) - A radix sorting library for Go.

## Assembly

- [mmcloughlin/avo](https://github.com/mmcloughlin/avo) - Generate x86 Assembly with Go.
- [CAFxX/atomics](https://github.com/CAFxX/atomics) - All the missing AMD64 atomic instructions.

## Benchmarks

- [benchstat](https://godoc.org/golang.org/x/perf/cmd/benchstat) - Benchstat computes and compares statistics about benchmarks.
- [go-benchrun](https://github.com/quasilyte/go-benchrun) - Convenience wrapper around "go test" + "benchstat".

## Compiling

- [gcassert](https://github.com/jordanlewis/gcassert) - Assert your Go code is inlined and bounds-check eliminated.

## Concurrency

- [grmon](https://github.com/bcicen/grmon) - Command line monitoring for goroutines.
- [drwmutex](https://github.com/jonhoo/drwmutex) - Distributed RWMutex in Go.

## Crypto

- [md5-simd](https://github.com/minio/md5-simd) - Accelerate aggregated MD5 hashing performance up to 8x for AVX512 and 4x for AVX2.

## GC

- [gcnotifier](https://github.com/CAFxX/gcnotifier) - Know when GC runs from inside your golang code.

## Hardware

- [klauspost/cpuid](https://github.com/klauspost/cpuid) - Provides information about the CPU running the current program.

## Hash


## IO

- [preallocate](https://github.com/smallnest/preallocate) - File preallocation library

## Math

- [fastdiv](https://github.com/bmkessler/fastdiv) - Fast division, modulus and divisibility checks in Go for divisors known only at runtime.

## Network

- [fasthttp](https://github.com/valyala/fasthttp) - Fast HTTP package for Go. Tuned for high performance. Zero memory allocations in hot paths. Up to 10x faster than net/http.
- [fiber](https://github.com/gofiber/fiber) - Fiber is an Express inspired web framework built on top of Fasthttp, the fastest HTTP engine for Go. Designed to ease things up for fast development with zero memory allocation and performance in mind.
- [gnet](https://github.com/panjf2000/gnet) - high-performance, lightweight, non-blocking, event-driven networking framework written in pure Go. Ranks #10 in TechEmpower Plaintext Benchmark, beating all other go frameworks.


## Profiling

- [profefe](https://github.com/profefe/profefe) - Continuous profiling data collecting.
- [google/pprof](https://github.com/google/pprof) - pprof is a tool for visualization and analysis of profiling data.
- [felixge/fgprof](https://github.com/felixge/fgprof) - a sampling Go profiler that allows you to analyze On-CPU as well as Off-CPU (e.g. I/O) time together.
- [parca](https://parca.dev) - Parca is a continuous profiling project for applications and infrastructure, built with Go for Go.

## Storage

- [stringbank](https://github.com/philpearl/stringbank) - Storing strings without GC overhead.

## Testing

## Articles

- [The official HOW-TO on app diagnostics](https://golang.org/doc/diagnostics.html).
- [Debugging performance issues in Go programs by Dmitry Vyukov (2014)](https://archive.is/TIkLM).
- [Go Wiki: Compiler And Runtime Optimizations](https://github.com/golang/go/wiki/CompilerOptimizations)

## Other

- [templexxx/tsc](https://github.com/templexxx/tsc) - Get unix time (nanoseconds) in 8ns, 10x faster than stdlib.
