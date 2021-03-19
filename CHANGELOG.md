# Changelog

# main
[Full Changelog](https://github.com/mtrezza/parse-server-api-mail-adapter/compare/1.0.5...master)

### ⚠️ Breaking Changes
*(none)*

### 🚀 Notable Changes
*(none)*

### 🧬 Other Changes
- Fixes failing to send email in Cloud Code without template (Manuel Trezza) [#26](https://github.com/mtrezza/parse-server-api-mail-adapter/pull/26)

# 1.0.5
[Full Changelog](https://github.com/mtrezza/parse-server-api-mail-adapter/compare/1.0.4...1.0.5)

### ⚠️ Breaking Changes
*(none)*

### 🚀 Notable Changes
*(none)*

### 🧬 Other Changes
- Fixes undefined `user` in `localeCallback` when sending email via `Parse.Cloud.sendEmail()` (wlky, Manuel Trezza) [#18](https://github.com/mtrezza/parse-server-api-mail-adapter/pull/18)

# 1.0.4
[Full Changelog](https://github.com/mtrezza/parse-server-api-mail-adapter/compare/1.0.3...1.0.4)

### 🐛 Fixes
- Fixed failing Parse Server adapter controller validation. [#13](https://github.com/mtrezza/parse-server-api-mail-adapter/pull/13). Thanks to [mtrezza](https://github.com/mtrezza).

### 🧬 Improvements
- Added lint to CI workflow. [#14](https://github.com/mtrezza/parse-server-api-mail-adapter/pull/14). Thanks to [mtrezza](https://github.com/mtrezza).

# 1.0.3
[Full Changelog](https://github.com/mtrezza/parse-server-api-mail-adapter/compare/1.0.2...1.0.3)

### 🐛 Fixes
- Added missing release script invocation when publishing package to npm. [#11](https://github.com/mtrezza/parse-server-api-mail-adapter/pull/11). Thanks to [mtrezza](https://github.com/mtrezza).

# 1.0.2
[Full Changelog](https://github.com/mtrezza/parse-server-api-mail-adapter/compare/1.0.1...1.0.2)

### 🧬 Improvements
- Added locale to placeholder callback. [#6](https://github.com/mtrezza/parse-server-api-mail-adapter/pull/6). Thanks to [mtrezza](https://github.com/mtrezza).
- Added current placeholders to placeholder callback. [#7](https://github.com/mtrezza/parse-server-api-mail-adapter/pull/7). Thanks to [mtrezza](https://github.com/mtrezza).

# 1.0.1
[Full Changelog](https://github.com/mtrezza/parse-server-api-mail-adapter/compare/1.0.0...1.0.1)

### 🐛 Fixes
- Removed unused config parameter from docs. [#1](https://github.com/mtrezza/parse-server-api-mail-adapter/pull/1). Thanks to [mtrezza](https://github.com/mtrezza).

### 🧬 Improvements
- ⚠️ Added locale to API callback. This is a breaking change because the `apiCallback` now returns an object `{payload, locale}` instead of only the `payload`. [#2](https://github.com/mtrezza/parse-server-api-mail-adapter/pull/2). Thanks to [mtrezza](https://github.com/mtrezza)
- Added badges to readme. [#3](https://github.com/mtrezza/parse-server-api-mail-adapter/pull/3). Thanks to [mtrezza](https://github.com/mtrezza)

# 1.0.0
- Initial commit.