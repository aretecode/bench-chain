# 0.4.4
- 📊 added current results to not use every single result which can max things out
- ℹ️️ jsdocs for data adding with Results
- 🛁 some configstore cleaning in Results
- ⚒🔢 temp fix for slower/faster numbers
- 🎀 prettier name for suiteName when using path, prettier objformat
- 🖼️📦⬇ use mozilla polyfil for padEnd inline, less deps
- 📈 added reporting of ops, slicing only most recent messages
- 📜 script running examples
- %📊 pct report improvements & 🛁 clean!
- 📘 example of using for just a single benchmark
- ⛓ put suite in store - breaking

# 0.4.3
- 📛 fix tag reporting with referencing parent instead of reporter

# 0.4.2
- 🌀 fix ending spinner missed timeout alongside the interval
- ⚙ fix json parsing in obj-chain-plugin-config

# 0.4.1

- 📒🚚 move memory helpers and other data into deps file
- 📦⬆ added deps (table, some lodash, script-chain for auto-progress, obj-chain for config)
- 🔬 adding more tests
- ⚙💽 adding config store
- 🖼️ add screenshots
- 🏛️🏰 refactor reporting from Reporter, into
  - % PercentReporter
  - 📊 GraphReporter
  - # TagReporter
- 🛁 take out avggraphsinone until it works
- 🌀 add spinner, split into UI
- 🤸 split BenchChain out of index into a file
- 🆙📘 examples
- 🔗 update docs links
- 👂 add more subscribing methods
- 👾 simplify some ops
- ⛓ convert to more chainable store methods
- 🚩 more cli options
- ℹ️️ more jsdocs

# 0.4.0
- ⚒💍 fix async reporting some properties only being added to last cycle, just added to all now (bigger data but simpler code)
- [...] auto-progress bars

# 0.3.0
- add name to suite
- add more fluent
- add docs for new stuff
- added percent calc, likely needs improvements
- more examples

# 0.2.0 🔋⏱⛓📊👾
- 🔋 battery parsing from plist when available
- 🔋 battery in benchmark recordings
- ⏱ microtime in recordings
- ⛓ extend chainable
- 📊 format microtime recordings
- 👾 simplify async benchmarks
- 🤸 split reports into another class
- 🔬 fix test folder name and add another super simple basic instantiation test
- 📈📉 more nice graphs
