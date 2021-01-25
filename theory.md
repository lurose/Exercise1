Exercise 1 - Theory questions
-----------------------------
 
 ### What is the difference between concurrency and parallelism?
 > Parallelism - splits the tasks up into subtasks which can be processed in parallel. Needs to have at least one thread running.
 > Concurrency - be able to process two or more tasks at the same time - overlapping time periods. Consists often of one single CPU.
 
 ### Why have machines become increasingly multicore in the past decade?
 > Because multicore allow higher performance at lower energy - is more energy-efficient. We live in a digitized world, where a lot of our everyday stuff are dependent on computers/machines in some way.
 
 ### Why do we divide software (programs) into concurrently executing parts (like threads or processes)?
 (Or phrased differently: What problems do concurrency help in solving?)
 > Increased program throughput, more appropriate program structure and allow the "input/output"-waiting time in one task to be used for another task.
 > It help in solving problems where you need to run processes at the same time with shared resources.
 
 ### Does creating concurrent programs make the programmer's life easier? Harder? Maybe both?
 (Come back to this after you have worked on part 4 of this exercise)
 > I guess it will both make it easier and harder. Concrrent programs allow you to deal with more than one thing at the same time with overlapping time periods, but at the same time it can become quite complex? Not sure, will come back to this.
 
 ### What is the conceptual difference between threads and processes?
 > Process us a program in execution
 > Thread is the segment of a process, and consumes less resources
 
 ### Some languages support "fibers" (sometimes called "green threads") or "coroutines"? What are they?
 > *Your answer here*
 
 ### What is the Go-language's "goroutine"? A C/POSIX "pthread"?
 > *Your answer here*
 
 ### In Go, what does `func GOMAXPROCS(n int) int` change? 
 > *Your answer here*



 
 
 
 
