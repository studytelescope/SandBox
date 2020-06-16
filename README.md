# Introduction

Here is a simple project which demonstrates opportunuties of the RoaringBitmap library.

## Structure overview

``
.
├── benchmarks
│   ├── graphs
│   │   ├── All benchmarks.png
│   │   ├── BenchmarkFindFirstBitInFeature().png
│   │   ├── BenchmarkFindFirstBitInFeaturesContainer(), Changing variable : features_number.png
│   │   ├── BenchmarkFindFirstBitInFeaturesContainer().png
│   │   └── BenchmarkFindObjectsForFeature().png
│   └── search_bench_test.go
├── bin
│   └── programm
├── cmd
│   └── main.go
├── Makefile
├── pkg
│   ├── query
│   │   └── queries_methods.go
│   ├── search
│   │   └── search_methods.go
│   └── timelabel
│       └── timelabel.go
├── README.md
└── tests
    ├── manual_tests.go
    ├── queries_test.go
    └── search_test.go
``