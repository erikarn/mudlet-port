
PORTNAME=	mudlet
PORTVERSION=	4.19
CATEGORIES=	net games

USE_GITHUB=	yes
GH_ACCOUNT=	Mudlet
GH_PROJECT=	Mudlet

# release-4.19
GH_TAGNAME=	${GH_COMMIT}
GH_COMMIT=	f5516c3

# Generated via the submodules2tuple port
#
# submodules2tuple https://github.com/Mudlet/mudlet -b release-4.19

GH_TUPLE=	Mudlet:dblsqd-sdk-qt:c3c279fe:dblsqdsdkqt/3rdparty/dblsqd \
		Mudlet:edbee-lib:46086e00:edbeelib/3rdparty/edbee-lib \
		martin-eden:lua_code_formatter:4aa25029:lua_code_formatter/3rdparty/lcf \
		Mudlet:qt-ordered-map:ca2a31b7:qtorderedmap/3rdparty/qt-ordered-map \
		Mudlet:qtkeychain:ea7e748a:qtkeychain/3rdparty/qtkeychain \
		microsoft:vcpkg:a9dc9a4b:vcpkg/3rdparty/vcpkg


MAINTAINER=	adrian@FreeBSD.org
COMMENT=	A popular Qt based graphical MUD client

USES=		cmake lua51 lua51-luarocks pugixml sqlite3 yajl boost-libs pcre2
USE_QT6=	core gui network qmake buildtools keychain

# TODO: the following luarocks are also needed
# luautf8 luafilesystem lua-zip luasql-sqlite3 lrexlib-pcre lua-yajl

.include <bsd.port.mk>
