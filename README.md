# phpBB Selective Quoting
Selective Quoting mod for phpBB 3.0.12 (Prosilver theme).

## Manual installation

### Copy phpbb-selective-quoting.min.js to
```
/styles/prosilver/template/
```
### Modify template file
```
/styles/prosilver/template/viewtopic_body.html
```
Insert below code
```javascript
<script type="text/javascript" src="/styles/prosilver/template/phpbb-selective-quoting.min.js"></script>
```
before
```
<!-- INCLUDE overall_footer.html -->
```
###Delete cached file
```
/cache/tpl_prosilver_viewtopic_body.html.php
```
## Auto installation
Use AutoMOD and upload .zip package of this project.
## Usage
Just select text and press quote button.

If you do not select any text, default action will be triggered.

## Required phpBB settings
Quick reply must be enabled.
