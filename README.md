# Bible Data for APIs

This repository contains a comprehensive database of Bible translations in JSON format.

## Overview

The `bibles.json` file contains metadata for various Bible translations, including historical and modern versions. Each Bible entry includes detailed information about the translation, copyright status, and available features.

## Bible Translations Included

### Historical English Translations
- **Tyndale Bible** (1534) - William Tyndale's translation
- **Coverdale Bible** (1535) - Miles Coverdale translation
- **Geneva Bible** (1587)
- **Bishops Bible** (1568)
- **King James Version (KJV)** (1611/1769)

### Modern English Translations
- **American Standard Version (ASV)** (1901)
- **World English Bible (WEB)** (2006)
- **NET Bible®** (1996-2016)

### Enhanced Versions
- **KJV with Strong's Numbers**
- **ASV with Strong's Numbers**

## Data Structure

Each Bible entry contains:
- `name` - Full name of the translation
- `shortname` - Abbreviated name
- `module` - Internal module identifier
- `year` - Publication year
- `publisher` - Publishing organization
- `lang` - Full language name
- `lang_short` - Language code
- `copyright` - Copyright status (0 = Public Domain, 1 = Copyrighted)
- `copyright_statement` - Copyright information
- `strongs` - Strong's numbers availability
- `italics` - Italicized text support
- `red_letter` - Red letter edition support
- `official` - Official translation status
- `research` - Research edition availability

## Usage

The JSON file can be used to:
- Build Bible reading applications
- Create translation comparison tools
- Generate Bible study resources
- Develop API endpoints for Bible data

## Copyright Notice

Most translations in this database are in the Public Domain. However, some have specific copyright restrictions:
- **KJV**: Under perpetual Crown copyright in the United Kingdom
- **NET Bible®**: Copyright ©1996, 2016 Biblical Studies Press, L.L.C.

Always check the `copyright_statement` field before using any translation commercially.
