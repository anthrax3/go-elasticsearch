# Simple Elasticsearch 6.x API for Golang

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Build Status](https://travis-ci.org/Codehardt/go-elasticsearch.svg?branch=master)](https://travis-ci.org/Codehardt/go-elasticsearch)
[![GoDoc](https://godoc.org/github.com/Codehardt/go-elasticsearch?status.svg)](https://godoc.org/github.com/Codehardt/go-elasticsearch)

## Features

- Document 
  - Insert document
  - Update document
  - Delete document
  - Get document
  
- Query
  - Update documents by query
  - Delete documents by query
  - Get documents by query (paging)
  - Get documents by query (scroll)
  
- Bulk
  - Insert documents (Coming soon)
  
- Index
  - Delete index
  - Refresh index
  - Add Template
  - Delete Template
  
- Aggregate
  - Term Aggregate (Get most frequent values of a field)
  - Range Aggregate (Get min- and max-value of a field)
  - Cardinality Aggregate (Get unique count of a field)
  
- Other
  - Connection test
  - Health status
  - Optional debug logs
