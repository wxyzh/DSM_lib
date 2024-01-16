# For 7.2.1-69057-3

synoindexutils::IndexIsPathRemoteOrImageMount return 0ll;

synoindexutils::IndexIsPathRemoteMount return 0ll;

PatchELFSharp libmediaindex.so "IndexIsPathRemoteMount" "B8 00 00 00 00 C3"
PatchELFSharp libmediaindex.so "IndexIsPathRemoteOrImageMount" "B8 00 00 00 00 C3"
