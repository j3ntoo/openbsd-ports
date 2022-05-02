COMMENT = Japanese SKK input methods for Fcitx

GH_ACCOUNT = fcitx
GH_PROJECT = fcitx-skk
GH_TAGNAME = 0.1.4

CATEGORIES = inputmethods
MAINTAINER = atuow <atuow@xiun.org>

PERMIT_PACKAGE = Yes

WANTLIB += glib-2.0 gobject-2.0 intl skk

MASTER_SITES = ${MASTER_SITES_GITHUB}

MODULES = devel/cmake

BUILD_DEPENDS = devel/gettext,-tools
RUN_DEPENDS = inputmethods/fcitx japanese/skk-jisyo
LIB_DEPENDS = inputmethods/libskk

CONFIGURE_ARGS = -DENABLE_QT=Off -DSKK_DEFAULT_PATH=/usr/local/share/skk/SKK-JISYO.L

NO_TEST = Yes

.include <bsd.port.mk>
