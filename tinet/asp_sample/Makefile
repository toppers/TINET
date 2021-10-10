#
#  ネットワークサービスの定義
#

#  ネットワークインタフェースの選択、何れか一つ選択する。

NET_IF = @(NET_IF)

#  イーサネット・ディバイスドライバの選択

NET_DEV = @(NET_DEV)

#  ネットワーク層の選択

@(SUPPORT_INET6)
@(SUPPORT_INET4)

#  API に組込む機能の選択

@(API_CFG_IP4MAPPED_ADDR)

#  トランスポート層の選択

@(SUPPORT_TCP)
@(SUPPORT_UDP)

#
#  システムサービスの Makefile のインクルード
#
include $(SRCDIR)/tinet/Makefile.tinet

#
