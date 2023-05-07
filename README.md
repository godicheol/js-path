## Usage

```js
import jsPath from 'js-path';
```

```js
join("/dir1", "dir2", "dir3/dir4/dir5"); 
// dir1/dir2/dir3/dir4/dir5

join("/dir1", "dir2", "dir3/dir4/dir5", "..");
// dir1/dir2/dir3/dir4

parse("/dir1", "dir2", "dir3/dir4/dir5", "gg.txt");
// {
//     path: 'dir1/dir2/dir3/dir4/dir5/gg.txt',
//     type: 'text/plain',
//     name: 'gg',
//     extension: '.txt'
// }
```