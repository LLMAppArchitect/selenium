0.4.15
======
* Include mirror arguments to change default online repository URLs (#11687)
* Support for automatic management of Firefox ESR (#12946)
* Fix webview2 support (#12966)
* Include checkbox in SM workflow to generate binaries with debug symbols (#12974)
* Include flag in workflow to build SM in CI with debug info
* Include debug and split-debuginfo in dev profile
* Change windows target to stable-i686-pc-windows-gnu
* Bump all crates to the last versions (#13028)
* Fix conditions to check edge in cache (#13057)

0.4.14
======
* Use original browser version in Firefox management logic
* Clean logic for checking driver version
* Avoids resolving symbolic links and consider the cache might not be writable (#12877)
* Include webview2 in Edge module (#12904)
* Capture Rust backtrace in case of error (displayed at DEBUG level) (#12852)
* Automated Edge management (#11681 and #11683) (#12835)
* Add support for Chromium (#12511) (#12890)

0.4.13
======
* Ensure logger is set first so other setters can use it (#12720)
* Avoid using robocopy to move extracted files from sfx in windows (#12690)
* Make sure offline sets associated flags (#12718)
* Do not log a warning for defaults (#12754)
* Search better driver possible in the cache (#12753)
* Use original path when unwrap fails in canonicalize function (#12699)
* Fix config setup in Selenium Manager (#12807)

0.4.12
======
* Build universal macOS Selenium-Manager on CI (#12455)
* Fix bug in condition to check stable label (#12472)
* Implement browser path discovery for iexplorer (#12489)
* Fix bug storing metadata for iexplorer (#12488)
* Change default type for binaries downloaded by Selenium (#11685, #12485)
* Allow changing default folder for Selenium Manager cache (#11688, #12514)
* Fix bug with storing browser path when found in PATH
* Set permissions before copying extracted files
* Force executable permissions on extracted drivers
* Unify browser_ttl and driver_ttl (#12526)
* Rename configuration file to se-config.toml (#12550)
* Rename metadata file to se-metadata.json (#12531)
* Automated Firefox management (#11680 and #11682)
* Bump dependencies to the latest versions (#12601)
