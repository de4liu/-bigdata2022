# MSBA 6331 Big Data Analytics (Fall 2025)


## Commands

* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.
* `mkdocs gh-deploy` - Deploy the projects to github

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.


This repository servers as a public homepage for MSBA 6331 - Big Data Analytics at the Carlson School, University of Minnesota. It also hosts the syllabus and FAQs. 

[public homepage page](https://de4liu.github.io/bigdata/)

## Syllabus
- [Syllabus](syllabus.html): also [public syllabus](https://de4liu.github.io/bigdata/syllabus.html)

## Homework Related Instructions & Questions
- [Homework Guidelines](faqs/homework-guidelines.md)
- [Submit an ipynb file with image](faqs/addimage.md)
- [How to convert markdown to PDF](faqs/markdown2pdf.md)

## Computing environment

<!-- - [Apply for AWS Education](https://docs.google.com/document/d/1kB2TBG3gpWQLQO8Xyg6iiZVm3CnbB8lHtx97C_pqLdM/edit) -->
- [AWS setup instructions](https://docs.google.com/document/d/11ops7258BSfQcBevS20-ONISQymn-gyNXCMHBB5aL1k/edit#)
<!-- - [Vagrant: Introduction & Quick Reference](faqs/vagrant.md) -->
<!-- - [How to reduce the size of the Cloudera VM](faqs/rebuild_vm.md) -->
<!-- - [How to update the Vagrant folder](faqs/update_vagrant.md) -->
<!-- - [Install Cloudera VM on MSBA desktop](faqs/installVmCloud.md) -->
<!-- - [Install Cloudera VM on your own computer](faqs/installVM.md) -->

- [Install Spark Updates on Cloudera VM](faqs/installSparkUpdates.md): if you run into issues, here are [suggestions for diagnosis](faqs/diagnoseSparkUpdates.md)


## Hadoop
- [How to edit Linux text/script files](faqs/edit_linux_file.md)
- [How to convert Windows line endings to Linux ones](faqs/line_endings.md)
- [How to debug Hadoop streaming programs outside of Hadoop](faqs/debug_hadoop_streaming.md)
<!-- - [How to Debug MapReduce Jobs](faqs/debug_hadoop.md) -->

## Hive
- [How to Fix Hive metastore db error](faqs/hive_debug.md)

## Databricks & Spark
- [Install Apache Spark on your own computer](faqs/installLocalSpark.md): Install Apache Spark Virtual Machine with many featrues on your own computer (but no hadoop or Hive). This may take a while (e.g. 1 hour) to have everything ready.
- [Use DataBricks Community Edition for Spark](https://databricks.com/try-databricks): Databricks provides a single node spark cluster for free. It is quite easy to start it with a Jupyter note environment. 
- [Mount s3 folder in Databricks](faqs/mounts3.md)
<!-- - [Install JsonSerDe on your Cloudera VM](faqs/installJsonSerDe.md) -->
- [Common Issues with Running PySpark](faqs/sparkfaq.md): Addresses a few common issues with running PySpark on Cloudera VM.

## MISC
<!-- - [Install Teamviewer to enable instructor remote access to your MSBA virtual desktop](faqs/teamviewer.md) -->
- [Recommended text editors](faqs/textEditor.md)
- [Windows command 101](faqs/windows_cmd.md)
- [How to View Delimiters and Invisible Characters](faqs/viewdelimiters.md)
- [Configure Git](faqs/configGit.md)
- [Cheatsheet for Git](faqs/cheatsheet_git.md)

