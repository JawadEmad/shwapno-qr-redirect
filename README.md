# shwapno-qr-redirect<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shwapno App Download</title>
    <script type="text/javascript">
        // Detect the user's device
        var userAgent = navigator.userAgent || navigator.vendor || window.opera;

        if (/android/i.test(userAgent)) {
            // Redirect to Android Play Store
            window.location.href = "https://play.google.com/store/apps/details?id=com.shwapno";
        } else if (/iPad|iPhone|iPod/.test(userAgent) && !window.MSStream) {
            // Redirect to iOS App Store
            window.location.href = "https://apps.apple.com/us/app/shwapno-best-price-in-bd/id1567733501";
        } else {
            // Redirect to a fallback (your website or a message for unsupported devices)
            window.location.href = "https://www.shwapno.com/";
        }
    </script>
</head>
<body>
    <p>Redirecting to the appropriate app store...</p>
</body>
</html>
