### cyclops
---
https://github.com/aol/cyclops

```java
List<Integer> arrayList = new ArrayList<>();
arrayList.add(10);
arrayList.add(20);
arrayList.remove(10);

Vector<Integer> vector = Vector.of(10,20);
Vector<Integer> removed = vector.removeValue(10);


List<Integer> arrayList = new LinkedList<>();
arrayList.add(10);
arrayList.add(20);
arrayList.remove(10);

Seq<Integer> functionalLinkedList = Seq.of(10,20);
Seq<Integer> removed = functionalLinkedList.removeValue(10);


Stream<Integer> arrayList = Stream.of(1,2,3)
  .map(i->i*2);
  
LazySeq<Integer> arrayList = LazySeq.of(1,2,3)
  .map(i->i*2);
  
ReactiveSeq<Integer> arrayList = ReactiveSe.of(1,2,3)
  .map(i->i*2);
  
Optional<Integer> opt = Optional.empty();
if(opt.isPresent())
  return opt.get();
else
  return 0;

opt.get();



```

```
```

```
```
