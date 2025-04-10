可以修改https://github.com/kob/nf_deaf源码里nf_deaf.c的 payload 为你喜欢的内容，也可以在加载模块后修改/sys/kernel/debug/nf_deaf/buf 的内容，例如：
#define NF_DEAF_BUF_DEFAULT "GET / HTTP/1.1\r\n\
Host: www.speedtest.cn\r\n\
User-Agent: Mozilla/5.0\r\n\
Accept: */*\r\n\
Connection: close\r\n\
\r\n"Netfilter: Desynchronizing Evasion Against Filters
