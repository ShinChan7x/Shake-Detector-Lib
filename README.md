# Shake-Detector-Lib

Java Code On Create

```
Hasan hasan = new Hasan(new Hasan.OnShakeListener() {
    @Override
    public void onShakeDetected() {
        SketchwareUtil.showMessage(getApplicationContext(), "আপনার মোবাইল শেক করছে!");
    }
});

hasan.startShakeListener(this);
```
