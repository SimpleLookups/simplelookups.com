---
author: "Russell Patterson"
date: 2013-12-29 03:30:39+00:00
draft: false
title: SimpleLookups 1.2 Released
url: /2013/12/simplelookups-1-2-released/
---

Today, I released SimpleLookups v1.2. This version includes the following changes: 

New Features:
- Get a list of lookup values based on a code or a list of codes.
- Remove a list of lookup values based on a code or a list of codes.

Changed Features:
- The methods "GetActive" and "GetAll" are deprecated and are replaced by a single method called "Get". An activeOnly flag is passed in to the method.

The next release will be v1.5, and it will contain code structure changes and some other changes, namely the ability to configure SimpleLookups through app.config/web.config files.

