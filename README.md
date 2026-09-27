# Concurrency in .NET

Course repository covering threads, tasks, async/await, parallelism and synchronization primitives in .NET, one runnable example per concept.

## Projects

| Project | Contents |
|---|---|
| `ConsoleApp` | Threads, tasks, async/await, locking primitives |
| `ThreadSafeCollections` | `ConcurrentBag`, `ConcurrentQueue`, `ConcurrentStack`, `ConcurrentDictionary`, `BlockingCollection` |
| `ParallelForAndForeachExample` | `Parallel.For` and `Parallel.ForEach` |
| `MutexSingleProcessExamle` | Single-instance application via a named mutex |
| `WebApplication1` | Graceful shutdown and background consumers in ASP.NET Core |

## Topics Covered

- Threads: creation, priority, graceful shutdown, CPU-bound work (image processing)
- `Task`, `ValueTask`, cancellation and async patterns
- Race conditions and fixes with `lock`, `Monitor`, `Interlocked`
- `Mutex` and `SemaphoreSlim`
- Thread-safe collections and producer/consumer pipelines
- Data parallelism with the TPL
- Graceful shutdown in a hosted service

## Getting Started

```bash
git clone https://github.com/Fcakiroglu16/dotnet-concurrency-course.git
cd dotnet-concurrency-course
dotnet run --project ConsoleApp
```

Uncomment the example you want inside `ConsoleApp/Program.cs`.

## Requirements

- .NET SDK
