# Awesome Go performance

Collection of the Awesome™ Go libraries, tools, project around performance.

## Contents

- [Algorithm](#algorithm)
- [Assembly](#assembly)
- [Benchmarks](#benchmarks)
- [Compiling](#compiling)
- [Compression](#compression)
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

- [x/perf/cmd/benchstat](https://pkg.go.dev/golang.org/x/perf/cmd/benchstat) - Benchstat computes statistical summaries and A/B comparisons of Go benchmarks.
- [storozhukBM/benchart](https://github.com/storozhukBM/benchart) - Tool that takes `benchstat -csv` output as an input and plots results of your benchmark in a html file.
- [quasilyte/go-benchrun](https://github.com/quasilyte/go-benchrun) - Convenience wrapper around "go test" + "benchstat".

## Compiling

- [jordanlewis/gcassert](https://github.com/jordanlewis/gcassert) - Assert your Go code is inlined and bounds-check eliminated.

## Compression

- [klauspost/compress](https://github.com/klauspost/compress) - Optimized Go Compression Packages.
- [pierrec/lz4](https://github.com/pierrec/lz4) - LZ4 compression and decompression in pure Go.

## Concurrency

- [bcicen/grmon](https://github.com/bcicen/grmon) - Command line monitoring for goroutines.
- [jonhoo/drwmutex](https://github.com/jonhoo/drwmutex) - Distributed RWMutex in Go.

## Crypto

## GC

- [CAFxX/gcnotifier](https://github.com/CAFxX/gcnotifier) - Know when GC runs from inside your golang code.

## Hardware

- [klauspost/cpuid](https://github.com/klauspost/cpuid) - Provides information about the CPU running the current program.

## Hash

- [minio/md5-simd](https://github.com/minio/md5-simd) - Accelerate aggregated MD5 hashing performance up to 8x for AVX512 and 4x for AVX2.
- [zeebo/xxh3](https://github.com/zeebo/xxh3) - XXH3 algorithm in Go.

## IO

- [ncw/directio](github.com/ncw/directio) - This is library for the Go language to enable use of Direct IO under all OSes.
- [smallnest/preallocate](https://github.com/smallnest/preallocate) - File preallocation library.

## Math

- [bmkessler/fastdiv](https://github.com/bmkessler/fastdiv) - Fast division, modulus and divisibility checks in Go for divisors known only at runtime.

## Network

- [valyala/fasthttp](https://github.com/valyala/fasthttp) - Fast HTTP package for Go. Tuned for high performance. Zero memory allocations in hot paths. Up to 10x faster than net/http.
- [gnet](https://github.com/panjf2000/gnet) - high-performance, lightweight, non-blocking, event-driven networking framework written in pure Go.

## Profiling

- [profefe](https://github.com/profefe/profefe) - Continuous profiling data collecting.
- [google/pprof](https://github.com/google/pprof) - pprof is a tool for visualization and analysis of profiling data.
- [felixge/fgprof](https://github.com/felixge/fgprof) - a sampling Go profiler that allows you to analyze On-CPU as well as Off-CPU (e.g. I/O) time together.
- [parca](https://parca.dev) - Parca is a continuous profiling project for applications and infrastructure, built with Go for Go.
- [pyroscope](https://pyroscope.io/) - A modern open source continuous profiling platform for debugging Go performance issues down to a single line of code. 

## Storage

- [philpearl/stringbank](https://github.com/philpearl/stringbank) - Storing strings without GC overhead.

## Testing

## Articles

- [The official HOW-TO on app diagnostics](https://golang.org/doc/diagnostics.html).
- [Debugging performance issues in Go programs by Dmitry Vyukov (2014)](https://archive.is/TIkLM).
- [Go Wiki: Compiler And Runtime Optimizations](https://github.com/golang/go/wiki/CompilerOptimizations)
- [High Performance Go workshop by Dave Cheney (2019)](https://dave.cheney.net/high-performance-go-workshop/sydney-2019.html)

## Other

- [templexxx/tsc](https://github.com/templexxx/tsc) - Get unix time (nanoseconds) in 8ns, 10x faster than stdlib.
