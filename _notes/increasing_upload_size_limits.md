---
title: Increasing upload size limits PHP
---

**_php.ini_**

```php
post_max_size = 20M
upload_max_filesize = 20M
max_file_uploads = 20
```

```markdown
Modify the highlighted value for post_max_size as desired
(example: 30M, or 40M, or 50M).

Modify the highlighted value for upload_max_filesize as desired (example: 30M, or 40M, or 50M).
This value should not be larger than the post_max_size value.

Modify the highlighted value for max_file_uploads as desired
(example: 30, or 40, or 50).
```
