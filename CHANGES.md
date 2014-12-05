# 0.0.5opower1

* Support binary kafka payloads (Cherry-picked f203e1a9 from https://github.com/bpot/poseidon/pull/74)

# 0.0.5 (Unreleased)

* Fix serious bug where we would send messages to the wrong partition [GH-36]. (Thanks @sclasen and @jorgeortiz85 for tracking this down.)

# 0.0.4

* Don't truncate UTF8 Messages [GH-18]
* Gracefully handle truncated fetch reponses [GH-19]

# 0.0.3

* Better distribute messages across partitions.
* Handle broken connections better.
* Gracefully handle attempts to send an empty set of messages.

# 0.0.2

* Added ability to create a partitioner consumer for a topic+partition using topic metadata.
* Added PartitionConsumer#offset to return offset of the last fetch

# 0.0.1

* Initial release
