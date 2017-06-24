# ShouldJS Sublime Text 2 & 3 Snippets

This is a package for Sublime Text 2 & 3 that provides autocompletion for the [ShouldJS](https://shouldjs.github.io/) assertion library. It supports only calls in the format `should(target).assertion(expectation)`.

![](/ShouldJsSnippets.gif)

## Installation

#### 1. Package Control

Look for ShouldJsSnippets.

#### 2. Through git

1. Go to your packages folder (in Sublime : Preferences > Browse Packages…).
2. Clone the repo `git clone https://github.com/jmnsf/ShouldjsSnippets.git`

#### 3. Manually

Download this repo as a ShouldjsSnippets folder and save it into your packages (in Sublime : Preferences > Browse Packages…).

## Full Snippet List

### Equality

|**Trigger**|**Snippet**                            |
|-----------|---------------------------------------|
|sheq       |`should(target).equal(expectation)`    |
|sheql      |`should(target).eql(expectation)`      |
|shdeq      |`should(target).deepEqual(expectation)`|

### Booleans

|**Trigger**|**Snippet**                  |
|-----------|-----------------------------|
|sht        |`should(target).be.true()`   |
|shf        |`should(target).be.false()`  |
|shok       |`should(target).be.ok()`     |
|shnok      |`should(target).not.be.ok()` |

### Matching

|**Trigger**|**Snippet**                                              |
|-----------|---------------------------------------------------------|
|shmt       |`should(target).match(str&#124;regex&#124;obj&#124;fun)` |
|shmtea     |`should(target).matchEach(regex&#124;fun)`               |
|shmtsm     |`should(target).matchSome(regex&#124;fun)`               |

### Numbers

|**Trigger**|**Snippet**                                    |
|-----------|-----------------------------------------------|
|shgt       |`should(target).be.greaterThan(n)`             |
|shgte      |`should(target).be.greaterThanOrEqual(n)`      |
|shlt       |`should(target).be.lessThan(n)`                |
|shlte      |`should(target).be.lessThanOrEqual(n)`         |
|shapprox   |`should(target).be.approximately(value, delta)`|
|shwithin   |`should(target).be.within(min, max)`           |
|shinf      |`should(target).be.Infinity()`                 |
|shnan      |`should(target).be.NaN()`                      |

### Strings

|**Trigger**|**Snippet**                        |
|-----------|-----------------------------------|
|shstart    |`should(string).startWith(prefix)` |
|shend      |`should(string).endWith(suffix)`   |

### Contain

|**Trigger**|**Snippet**                                     |
|-----------|------------------------------------------------|
|shcd       |`should(target).containDeep(expectation)`       |
|shcdo      |`should(target).containDeepOrdered(expectation)`|
|shceq      |`should(target).containEql(expectation)`        |

### Promises

|**Trigger**|**Snippet**                                    |
|-----------|-----------------------------------------------|
|shful      |`should(target).be.fulfilled()`                |
|shfwith    |`should(target).be.fulfilledWith(expectation)` |
|shrej      |`should(target).be.rejected()`                 |
|shrwith    |`should(target).be.rejectedWith(error)`        |
|shprom     |`should(target).be.a.Promise()`                |
|shfin      |`should(target).finally.matcher`               |

### Properties

|**Trigger** |**Snippet**                                                   |
|------------|--------------------------------------------------------------|
|shemp       |`should(target).be.empty()`                                   |
|shlen       |`should(target).have.length(expectation)`                     |
|shprop      |`should(target).have.property(name, value)`                   |
|shoprop     |`should(target).have.ownProperty(name)`                       |
|shprops     |`should(target).have.properties(expectation)`                 |
|shkeys      |`should(target).have.keys(...keys)`                           |
|shenum      |`should(target).have.enumerable(name, value)`                 |
|shenums     |`should(target).have.enumerables(...names)`                   |
|shproppath  |`should(target).have.propertyByPath(...path)`                 |
|shproppatheq|`should(target).have.propertyByPath(path).equal(value)`       |
|shpropdesc  |`should(target).have.propertyWithDescriptor(name, descriptor)`|

### Types

|**Trigger** |**Snippet**                                 |
|------------|--------------------------------------------|
|shbool      |`should(target).be.a.Boolean()`             |
|shstr       |`should(target).be.a.String()`              |
|shnum       |`should(target).be.a.Number()`              |
|shdate      |`should(target).be.a.Date()`                |
|sharr       |`should(target).be.an.Array()`              |
|sherr       |`should(target).be.an.Error()`              |
|shfun       |`should(target).be.a.Function()`            |
|shinst      |`should(target).be.instanceOf(constructor)` |
|shtype      |`should(target).be.type(expectation)`       |
|shnull      |`should(target).be.Null()`                  |
|shund       |`should(target).be.Undefined()`             |
|shobj       |`should(target).be.an.Object()`             |
|shclass     |`should(target).be.a.Class()`               |
|shargs      |`should(target).be.Arguments()`             |

## Contributing

Feel free to open up an issue/PR if you find anything missing or an error in the current snippets.

**Keywords**: shouldjs, snippets, javascript
