# Change Log - @subsquid/util-internal-archive-layout

This log was last generated on Mon, 07 Oct 2024 08:48:33 GMT and should not be manually modified.

## 1.0.0
Mon, 07 Oct 2024 08:48:33 GMT

### Breaking changes

- make getShortHash use last bytes

## 0.4.1
Thu, 25 Jul 2024 11:48:18 GMT

_Version update only_

## 0.4.0
Wed, 15 May 2024 10:11:41 GMT

### Minor changes

- Write raw blocks in fix-sized batches to fix reproducilbility issues.

## 0.3.0
Wed, 17 Apr 2024 12:46:35 GMT

### Minor changes

- export `RawBlock` type

## 0.2.0
Sun, 17 Mar 2024 23:20:20 GMT

### Minor changes

- add `ArchiveLayout.getRawBlocks()`
- add `.topDirSize` option
- relax short block hash regex

### Patches

- fix: `ArchiveLayout.append()` should not try to extend passed block range when it is already completed

## 0.1.2
Thu, 29 Feb 2024 15:27:11 GMT

_Version update only_

## 0.1.1
Fri, 01 Dec 2023 16:55:51 GMT

### Patches

- update dependencies

## 0.1.0
Thu, 28 Sep 2023 20:58:19 GMT

### Minor changes

- feat: implement onSuccessWrite callback

### Patches

- update dependencies
- compile with TypeScript 5

## 0.0.1
Tue, 12 Sep 2023 08:42:04 GMT

_Version update only_

## 0.0.0
Wed, 19 Jul 2023 16:48:14 GMT

_Initial release_

