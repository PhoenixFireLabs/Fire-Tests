 * clone from https://github.com/PhoenixFireLabs/zxing (forked from https://github.com/zxing/zxing)

 * importing to IDE:

   - androidtest (zxing\androidtest) - main module
      depends:
        + android (zxing\android)
        + android-integration (zxing\android-integration)
        + android-core (zxing\android-core)
        + core (zxing\core)

   - android (zxing\android)
      depends:
        + android-core (zxing\android-core)
        + core (zxing\core)

   - android-integration (zxing\android-integration)
      no depends

   - android-core (zxing\android-core)
      no depends

   - core (zxing\core)
      no depends
