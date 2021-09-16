# Dvision’s API

## Dvision

### 1. Join Membership
```
[URL]
../api/join_ex

[POST]
country (string(100))
phone (string(255))
email (string(255))
account (string(255))
password (string(255))
name (string(255))
gender (string(10))
birth (string(20))
affiliation (string(255))
department (string(255))
position (string(255))
terms (string(-))
```

### 2. Login
```
[URL]
../api/login_ex

[POST]
account (string(255))
password (string(255))
```

### 3-1. Cert - SMS
```
[URL]
../api/cert_sms_ex

[POST]
country (string(100))
to (string(255))
```

### 3-2. Cert - Mail
```
[URL]
../api/cert_mail_ex

[POST]
country (string(100))
to (string(255))
name (string(255))
```

### 4. Check Cert
```
[URL]
../api/check_cert_ex

[POST]
to (string(255))
cert (string(255))
```

### 5. Find Accout
```
[URL]
../api/account_find_ex

[POST]
phone (string(255))
name (string(255))
```

### 6. Password_Tmp
```
[URL]
../api/password_tmp_ex

[POST]
country (string(100))
account (string(255))
phone (string(255))
```

### 7. Change Password
```
[URL]
../api/password_reset_ex

[POST]
phone (string(255))
account (string(255))
prev_password (string(255))
password (string(255))
```

### 7. Get Post List
```
[URL]
../api/post_get_list_ex

[POST]
type (int(1))
page (int(11))
count (int(11))
```

### 8. Get Post By Id
```
[URL]
../api/post_get_by_id_ex

[POST]
id (int(11))
```

### 9. Insert Post
```
[URL]
../api/post_insert_ex

[POST]
category (int(1))
title (string(255))
detail (string(255))
thumbnail (string(255))
popup (int(1))
ext_link (string(255))
footer_list_id (int(5))
```

### 10. Update Post
```
[URL]
../api/post_update_ex

[POST]
id(int(11))
category (int(1))
title (string(255))
detail (string(255))
thumbnail (string(255))
popup (int(1))
ext_link (string(255))
footer_list_id (int(5))

```

### 11. Delete Post
```
[URL]
../api/post_delete_ex

[POST]
id(int(11)) 

```

## Market
```
to be continued..🎁🎁🎁
```