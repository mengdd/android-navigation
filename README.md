# Android Navigation codelab

Content: https://codelabs.developers.google.com/codelabs/android-navigation/

## Notes
2 Ways to test deep link of this sample:

1:
```
adb shell am start -a android.intent.action.VIEW -d "http://www.example.com/urlTest" 
```

2:
Navigate via the Google app. 
You should be able to put `www.example.com/urlTest` in the search bar and the disambiguation window will appear. 
Select Navigation codelab.

License
-------

Copyright 2018 The Android Open Source Project, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the NOTICE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.