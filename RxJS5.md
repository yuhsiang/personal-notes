# Reactive Programming in Actino with RxJS5
[Grahistry](https://www.graphistry.com/)
time and space analogy

Generator es6
iterator
event handler
call that interactive programing...

Reactive Prgraming (obersavable)

# Duality
Generator <- iterator (synchronize)
obersable -> observer (inheraently snchronizable)

### Observable
ReactiveX is all about ...
RxJS + Angular 2
(tc39 proposes obersable soon..)

create obersable
subscribe and unsubscribe
when subscribe more than once
each observable is run in an isolated memory space

### Operatior
like lodash but the data from the future

### Schedulers
important concept in RxJS
call someone elses code that uses timer/ setinterval but forget to relesase
if could let you set your time => schedulers
you can pass in your own schedulers
ie test schedulers

## RxJS combines functional ...
### what can be obsersed ?
fromEvent..
interval
ajax
websocket
[flatmap](http://reactivex.io/documentation/operators/flatmap.html)
