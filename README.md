# Awesome Go performance

Collection of the Awesome™ Go libraries, tools, project around performance.

## Contents

- [Algorithm](#algorithm)
- [Assembly](#assembly)
- [Benchmarks](#benchmarks)
- [Concurrency](#concurrency)
- [Crypto](#crypto)
- [GC](#gc)
- [Hardware](#hardware)
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

## Concurrency

- [grmon](https://github.com/bcicen/grmon) - Command line monitoring for goroutines.
- [drwmutex](https://github.com/jonhoo/drwmutex) - Distributed RWMutex in Go.

## Crypto

- [md5-simd](https://github.com/minio/md5-simd) - Accelerate aggregated MD5 hashing performance up to 8x for AVX512 and 4x for AVX2.

## GC

- [gcnotifier](https://github.com/CAFxX/gcnotifier) - Know when GC runs from inside your golang code.

## Hardware

- [klauspost/cpuid](https://github.com/klauspost/cpuid) - Provides information about the CPU running the current program.

## IO

- [preallocate](https://github.com/smallnest/preallocate) - File preallocation library

## Math

- [fastdiv](https://github.com/bmkessler/fastdiv) - Fast division, modulus and divisibility checks in Go for divisors known only at runtime.

## Network

- [fasthttp](https://github.com/valyala/fasthttp) - Fast HTTP package for Go. Tuned for high performance. Zero memory allocations in hot paths. Up to 10x faster than net/http.

## Profiling

- [profefe](https://github.com/profefe/profefe) - Continuous profiling data collecting.
- [google/pprof](https://github.com/google/pprof) - pprof is a tool for visualization and analysis of profiling data.
- [felixge/fgprof](https://github.com/felixge/fgprof) - a sampling Go profiler that allows you to analyze On-CPU as well as Off-CPU (e.g. I/O) time together.

## Storage

- [stringbank](https://github.com/philpearl/stringbank) - Storing strings without GC overhead.

## Testing

## Articles

- [The official HOW-TO on app diagnostics](https://golang.org/doc/diagnostics.html).
- [Debugging performance issues in Go programs by Dmitry Vyukov (2014)](https://software.intel.com/en-us/blogs/2014/05/10/debugging-performance-issues-in-go-programs).

## Other
