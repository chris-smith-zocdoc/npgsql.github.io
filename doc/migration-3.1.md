---
layout: doc
title: Breaking changes in 3.1
---

* Since `Persist Security Info` is now implemented and is false by default, if you get the connection string of a connection
  that has been opened it will no longer contain the password.

