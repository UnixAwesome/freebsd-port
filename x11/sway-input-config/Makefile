PORTNAME=      sway-input-config
PORTVERSION=   1.4.1
DISTVERSIONPREFIX= v
CATEGORIES=    x11 wayland

MAINTAINER=    totalslinux@gmail.com
COMMENT=      Sway input settings

LICENSE=      GPLv3

USE_GITHUB=   yes
GH_ACCOUNT=   Sunderland93

BUILD_DEPENDS=  wayland-protocols>0:graphics/wayland-protocols \
RUN_DEPENDS=	  ${PYTHON_PKGNAMEPREFIX}pyqt6>0:devel/pyside6 \
		  ${PYTHON_PKGNAMEPREFIX}i3ipc>0:x11/py-i3ipc


USES=		python qt:6
USE_PYTHON=	autoplist distutils unittest



.include <bsd.port.mk>
