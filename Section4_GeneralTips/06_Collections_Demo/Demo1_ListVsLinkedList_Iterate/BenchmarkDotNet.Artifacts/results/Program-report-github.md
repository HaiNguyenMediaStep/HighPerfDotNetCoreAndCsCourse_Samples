``` ini

BenchmarkDotNet=v0.10.9, OS=Windows 10 Redstone 2 (10.0.15063)
Processor=Intel Core i5-5200U CPU 2.20GHz (Broadwell), ProcessorCount=4
Frequency=2143474 Hz, Resolution=466.5324 ns, Timer=TSC
.NET Core SDK=2.0.2-vspre-006949
  [Host]     : .NET Core 2.0.0 (Framework 4.6.00001.0), 64bit RyuJIT
  DefaultJob : .NET Core 2.0.0 (Framework 4.6.00001.0), 64bit RyuJIT


```
 |                              Method |       Mean |     Error |    StdDev |
 |------------------------------------ |-----------:|----------:|----------:|
 |       CheckForNonExistingItemInList |   888.8 us |  17.72 us |  25.98 us |
 | CheckForNonExistingItemInLinkedList | 5,951.5 us | 116.23 us | 146.99 us |
