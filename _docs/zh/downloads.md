---
permalink: docs/downloads/
---

我们推荐下载遵循[ASF Release Policy](http://www.apache.org/legal/release-policy.html)发布的源码包：

[2.1.0-src]: https://www.apache.org/dyn/closer.cgi?path=/incubator/pegasus/2.1.0/apache-pegasus-2.1.0-incubating-src.zip
[2.1.0-asc]: https://downloads.apache.org/incubator/pegasus/2.1.0/apache-pegasus-2.1.0-incubating-src.zip.asc
[2.1.0-sha]: https://downloads.apache.org/incubator/pegasus/2.1.0/apache-pegasus-2.1.0-incubating-src.zip.sha512
[2.1.0-rn]: https://cwiki.apache.org/confluence/x/cxbZCQ

Name | Package | Signature | Checksum | Release Notes |
---|---|---|---|---|
Apache Pegasus 2.1.0 | [Source][2.1.0-src] | [asc][2.1.0-asc] | [sha512][2.1.0-sha] | [2020-11-30][2.1.0-rn]

你也可以通过git clone的方式获取Pegasus源码：

```bash
git clone -b v2.1.0 --recursive https://github.com/apache/incubator-pegasus.git
```

在 2.1.0 版本以前，Pegasus 并未遵循 ASF 发版流程，这里我们仍然提供老版本下载渠道，方便升级：

[2.0.0-src]: https://github.com/apache/incubator-pegasus/releases/download/v2.0.0/apache-pegasus-2.0.0-incubating-src.zip
[2.0.0-rn]: https://github.com/apache/incubator-pegasus/releases/tag/v2.0.0
[1.12.3-src]: https://github.com/apache/incubator-pegasus/releases/download/v1.12.3/apache-pegasus-1.12.3-incubating-src.zip
[1.12.3-rn]: https://github.com/apache/incubator-pegasus/releases/tag/v1.12.3
[1.12.0-src]: https://github.com/apache/incubator-pegasus/releases/download/v1.12.0/apache-pegasus-1.12.0-incubating-src.zip
[1.12.0-rn]: https://github.com/apache/incubator-pegasus/releases/tag/v1.12.0
[1.11.6-src]: https://github.com/apache/incubator-pegasus/releases/download/v1.11.6/apache-pegasus-1.11.6-incubating-src.zip
[1.11.6-rn]: https://github.com/apache/incubator-pegasus/releases/tag/v1.11.6
[1.11.3-src]: https://github.com/apache/incubator-pegasus/releases/download/v1.11.3/apache-pegasus-1.11.3-incubating-src.zip
[1.11.3-rn]: https://github.com/apache/incubator-pegasus/releases/tag/v1.11.3
[1.10.0-src]: https://github.com/apache/incubator-pegasus/releases/download/v1.10.0/apache-pegasus-1.10.0-incubating-src.zip
[1.10.0-rn]: https://github.com/apache/incubator-pegasus/releases/tag/v1.10.0
[1.9.0-src]: https://github.com/apache/incubator-pegasus/releases/download/v1.9.0/apache-pegasus-1.9.0-incubating-src.zip
[1.9.0-rn]: https://github.com/apache/incubator-pegasus/releases/tag/v1.9.0

Name | Package | Release Notes
---|---|---
Apache Pegasus 2.0.0 | [Source][2.0.0-src] | [2020-6-11][2.0.0-rn]
Apache Pegasus 1.12.3 | [Source][1.12.3-src] | [2020-4-23][1.12.3-rn]
Apache Pegasus 1.12.0 | [Source][1.12.0-src] | [2019-11-19][1.12.0-rn]
Apache Pegasus 1.11.6 | [Source][1.11.6-src] | [2019-8-23][1.11.6-rn]
Apache Pegasus 1.11.3 | [Source][1.11.3-src] | [2019-2-27][1.11.3-rn]
Apache Pegasus 1.10.0 | [Source][1.10.0-src] | [2018-6-19][1.10.0-rn]
Apache Pegasus 1.9.0 | [Source][1.9.0-src] | [2018-6-20][1.9.0-rn]

上述各版本均可找到对应编译环境的镜像：<https://hub.docker.com/r/apachepegasus/build-env/tags>，请参考 [{{site.data.translate['title_compile-by-docker'}}](/docs/build/compile-by-docker/) 完成编译。

```
docker pull apachepegasus/build-env:{VERSION}-{OS}
```
