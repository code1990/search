12/26/2018 9:23:56 PM 
-------------------------------
##第 l 章介绍 ApacheLucene的工作方式,以及 ElasticSearch 的基本概念,并演示 Elastic-Search 的内部工作机制。
##第 2 章描述 Lucene 评分过程是如何工作的， 为什么要进行查询重写， 以及查询二次评分（ rescore ） 是如何工作的。 除此之外， 还将介绍 ElasticSearch 的批处理 API， 以及如何使用过滤器（filter ）来优化查询。
##第3章描述如何修改 Lucene 评分， 并使用不同的倒排索引格式来改变索引字段的结构。 此外还会介绍 ElasticSearch 的准实时搜索和索引， 事务日志的使用， 理解索引的段合并以及如何调整段合并来适应应用场景。
##第4章介绍以下技术： 如何选择恰当的索引分片及复制（ replicas）数量， 路由是如何 工作的， 索引分片机制是如何工作的以及如何影响分片行为。 同时还介绍 ElasticSearch 如何进行系统初始配置， 以及当数据量和查询量急剧增长时如何调整系统配置。
##第5章介绍如何为具体应用选择 正确的目录（ directory ）实现， 什么是发现( Discovery）、 网关（ Gateway ）、 恢复（ Recovery ）模块， 如何配置这些模块， 以及有哪些令人困扰的疑难点。 最后介绍如何通过 ElasticSearch 来查看索引段信息， 以及如何进行ElasticSearch 缓存机制的调优。
##第6章介绍 JVM 垃圾收集的工作原理和重要意义， 以及如何对它进行调优。 同时还介绍如何控制 ElasticSearch 的I/0操作数量， 什么是预热器（warmer）以及如何使用它， 最后介绍如何诊断 ElasticSearch 中的问题。
##第 7 章介绍查询建议（ suggester ）， 它能帮助修正查询中的拼写错误以及构建高效的自动完成（ autocomplete）机制。 除此之外， 将通过实际的案例展示如何使用不同查询类型和ElasticSearch 的其他功能来提高查询相关性。
##第8章覆盖 ElasticSearch 的 Java API，不仅包括一些基本A凹， 诸如连接到 ElasticSearch集群、 单条索引或批量索引、 检索文档等， 而且涵盖 ElasticSearch 暴露的一些用于控制集群的 API 。
##第9章通过演示如何开发你自己的河流（ river ）和语言处理（language ）插件来介绍 ElasticSearch 的插件开发。