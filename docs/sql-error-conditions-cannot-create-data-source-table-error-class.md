---
layout: global
title: CANNOT_CREATE_DATA_SOURCE_TABLE error class
displayTitle: CANNOT_CREATE_DATA_SOURCE_TABLE error class
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

[SQLSTATE: 42KDE](sql-error-conditions-sqlstates.html#class-42-syntax-error-or-access-rule-violation)

Failed to create data source table `<tableName>`:

This error class has the following derived error classes:

## EXTERNAL_METADATA_UNSUPPORTED

provider '`<provider>`' does not support external metadata but a schema is provided. Please remove the schema when creating the table.


