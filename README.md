# text4shell-scan-common-text-calls
Dockerbuild artefacts to build a container to that runs jfrog scan_commons_text_calls_jar.py
After you build the container, to run the container to scan vulnerable jar files for system calls referenced in CVE-2022-42889 using the scan_common_text_calls.py script developed by jfrog/text4shell-tools (Credit goes to jfrog!!!):
1 - CD into the folder you wish to scan
2 - docker run --rm -v $(pwd):/tmp <name of container you have built> /tmp
