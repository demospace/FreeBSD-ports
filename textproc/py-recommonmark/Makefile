# $FreeBSD$

PORTNAME=	recommonmark
PORTVERSION=	0.0.20180530
CATEGORIES=	textproc python
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	brooks@FreeBSD.org
COMMENT=	CommonMark bridge for docutils and Sphinx

LICENSE=	MIT
LICENSE_FILE=	${WRKSRC}/license.md

RUN_DEPENDS=	${PYTHON_PKGNAMEPREFIX}CommonMark>=0.7.3:textproc/py-CommonMark@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}docutils>=0.11:textproc/py-docutils@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}sphinx>=1.3.1:textproc/py-sphinx@${PY_FLAVOR}

USES=		python
USE_PYTHON=	autoplist distutils

USE_GITHUB=	yes
GH_ACCOUNT=	rtfd
GH_PROJECT=	recommonmark
GH_TAGNAME=	956bf18b24d48ff0b496d7464bc01a368fb97807

NO_ARCH=	yes

.include <bsd.port.mk>
