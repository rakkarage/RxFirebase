# RxFirebase
A wrapper for Google's Firebase library.

# Usage
### Kotlin
```
FirebaseDatabase.getInstance().reference.observeListOf(Sample::class.java)
```
Above code returns `Observable<List<Sample>>`

### Java
```
RxFirebaseDatabaseKt.observeListOf(FirebaseDatabase.getInstance().getReference(),
Sample.class)
```
Above code returns `Observable<List<Sample>>`

# Download
``` dependencies {
	compile 'io.github.jasvilladarez:rxfirebase:0.2.0'
}```

Add the following to your repositories

# License
Copyright 2016 Jasmine Villadarez

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.