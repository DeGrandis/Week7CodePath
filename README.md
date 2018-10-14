# Project 7 - WordPress Pentesting

Time spent: About 5-5:30 hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pentesting Report

1. (Required) WordPress <= 4.2.2 - Authenticated Stored Cross-Site Scripting (XSS) (8111)
  - [ ] Summary: 
    - Vulnerability types: Cross Site Scripting
    - Tested in version: 4.2
    - Fixed in version: 4.2.10
  - [ ] GIF Walkthrough: xss1.gif
  - [ ] Steps to recreate: 
        Single step in:  [Link 1](https://wpvulndb.com/vulnerabilities/8111)
  - [ ] Affected source code:
    - [Link 1](http://wpdistillery.vm/wp-admin/post-new.php)
2. (Required) Vulnerability Name or ID
  - [ ] Summary: WordPress <= 4.3 - Authenticated Shortcode Tags Cross-Site Scripting (XSS) (8186)
    - Vulnerability types: Cross Site Scripting
    - Tested in version: 4.2
    - Fixed in version: 4.3.1
  - [ ] GIF Walkthrough:  xss2.gif
  - [ ] Steps to recreate:
        Single Step in: [Link 1](https://wpvulndb.com/vulnerabilities/8186)
  - [ ] Affected source code: 
    - [Link 1](http://wpdistillery.vm/wp-admin/post-new.php)
3. (Required) WordPress <= 4.2.3 - Legacy Theme Preview Cross-Site Scripting (XSS)
  - [ ] Summary:  
    - Vulnerability types: Cross Site Scripting
    - Tested in version: 4.2
    - Fixed in version: 4.2.3
  - [ ] GIF Walkthrough: xss3.gif
  - [ ] Steps to recreate: [Link 1](https://blog.sucuri.net/2015/08/persistent-xss-vulnerability-in-wordpress-explained.html)
  - [ ] Affected source code:
    - [Link 1](http://wpdistillery.vm/wp-admin/comment.php?action=editcomment&c=9)
1. (Optional) Vulnerability Name or ID
  - [ ] Summary: 
    - Vulnerability types:
    - Tested in version:
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
1. (Optional) Vulnerability Name or ID
  - [ ] Summary: 
    - Vulnerability types:
    - Tested in version:
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php) 

## Assets

List any additional assets, such as scripts or files

## Resources

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)

GIFs created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while doing the work:
Performing exploits that weren't XSS was very dificult.  

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
