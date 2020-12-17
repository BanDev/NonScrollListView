# NonScrollListView

NonScrollListView is an extension of an android ListView that automatically sets hight so no scrolling is required. It is used throughout [Labyrinth](https://github.com/bandev/labyrinth) and more of our open source android apps.

## Usage

**Step 1.** Add it in your root build.gradle at the end of repositories:
```groovy
allprojects {
    repositories {
        maven { url 'https://jitpack.io' }
    }
}
```

**Step 2.** Add the dependency
```groovy
dependencies {
    implementation 'com.github.bandev:NonScrollListView:1.0.1'
}
```

**Step 3.** Add the view to your layout
```xml
<org.bandev.libraries.NonScroll.ListView
    android:id="@+id/listView"
    android:layout_width="match_parent"
    android:layout_height="wrap_content">

    ...
    
</org.bandev.libraries.NonScroll.ListView>

```

## License

This library is licensed under the [Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).

See [`LICENSE`](LICENSE) for full of the license text.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
