# js to bootstrap

# before
---
```
<form id="squareForm">
    <label for="N">Select your rate:</label>
    <input type="range" name="N" id="N" min="0" max="5000" value="1200" required>
    <span id="rateValue">1200</span>
    <br>
    <input type="submit" value="Submit">
</form>
```
---
# after
---
```
Bootstrap 5 CSSの読み込み
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css">
Bootstrap 5 JSの読み込み
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"></script>   
```
```
<form id="squareForm">
    <label for="N">Select your rate:</label>
    <div class="range">
        <input type="range" class="form-range" name="N" id="N" min="0" max="5000" value="1200" required>
    </div>
    <span id="rateValue">1200</span>
    <br>
    <input type="submit" **class="btn btn-primary"** value="Submit">
</form>
```
---
