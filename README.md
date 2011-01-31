The cluster_info application
============================

The `cluster_info` application provides a flexible and easily-extendible
way to dump the state of a cluster of Erlang nodes.

Some of the information that the application gathers includes:

* Date & time
* Statistics on all Erlang processes on the node
* Network connection details to all other Erlang nodes
* Top CPU- and memory-hogging processes
* Processes with large mailboxes
* Internal memory allocator statistics
* ETS table information
* The names & versions of each code module loaded into the node

The app can also automatically gather all of this data from all nodes
and write it into a single file. It's about as easy as can be to take
a snapshot of all nodes in a cluster. It is a valuable tool for
support and development teams to diagnose problems in a cluster, as a
tool to aid capacity planning, and merely to answer a curious question
like, "What's really going on in there?"

Licensing
---------

The `cluster_info` application was written by
[Gemini Mobile Technologies, Inc.](http://www.geminimobile.com/)
and is licensed under the
[Apache Public License version 2.0](http://www.apache.org/licenses/LICENSE-2.0).

