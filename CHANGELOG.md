## 1.5.2

* **Add upload options** add `responseType` and `withCredentials` with upload options.

* **Code optimization** Optimizate functions with check file size and type, make code more readable.

## 1.5.1

### Fix problem with IE

* **Append upload input elm on body:** IE need actual element on document, that can occur upload change event.

* **Change peerDependencies to more than 6.0.0:** Change peerDependencies to more than 6.0.0

## 1.5.0

### Refactory upload with Renderer

* Refactory upload with Renderer2 to add class and style
* **add skipInvalid to FileOption:** now you can use skipInvalid to ignore invalid file.

## 1.4.0

### Upgrade to Angular 6+ Rxjs 6+

* Upgrade to Angular 6+ Rxjs 6+

## 1.3.0

### Upgrade

* Beacuse big change with package way, so direct jump to 1.3.0, 
* API don't has BREAK CHANGE, just only add UploadEvent type to NgxfUploaderService. :)

## 1.2.7

### Bug fix

* **NgxfUploaderService fix type to `Observable<UploadEvent>`**

## 1.2.6

### Upgrade

* **upgrade to rxjs 5.5.7**
* **deprecated previous version**
