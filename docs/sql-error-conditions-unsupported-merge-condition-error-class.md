---
layout: global
title: UNSUPPORTED_MERGE_CONDITION error class
displayTitle: UNSUPPORTED_MERGE_CONDITION error class
license: |
  Licensed to the Apache Software Foundation (ASF) under one or more
  contributor license agreements.  See the NOTICE file distributed with
  this work for additional information regarding copyright ownership.
  The ASF licenses this file to You under the Apache License, Version 2.0
  (the "License"); you may not use this file except in compliance with
  the License.  You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

  Unless required by applicable law or agreed to in writing, software
  distributed under the License is distributed on an "AS IS" BASIS,
  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
  See the License for the specific language governing permissions and
  limitations under the License.
---

[SQLSTATE: 42K0E](sql-error-conditions-sqlstates.html#class-42-syntax-error-or-access-rule-violation)

MERGE operation contains unsupported `<condName>` condition.

This error class has the following derived error classes:

## AGGREGATE

Aggregates are not allowed: `<cond>`.

## NON_DETERMINISTIC

Non-deterministic expressions are not allowed: `<cond>`.

## SUBQUERY

Subqueries are not allowed: `<cond>`.


