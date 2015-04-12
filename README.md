# bloom
exported from code.google.com/p/bloom

Added support to serialization/deserialization of a bloom filter object to file.

#usage:
```
bloom_filter filter;
/* inserting stuff*/
filter.save(path);

/*later*/
bloom_filter f2;
f2.load(path);

assert(f2==filter);
```
