# $FreeBSD$

PORTNAME=	snap
PORTVERSION=	1.1.1.0
CATEGORIES=	www haskell

MAINTAINER=	haskell@FreeBSD.org
COMMENT=	Top-level package for the Snap Web Framework

LICENSE=	BSD3CLAUSE

USE_CABAL=	aeson attoparsec cereal clientsession configurator \
		directory-tree dlist hashable heist lens lifted-base \
		map-syntax monad-control mtl mwc-random pwstore-fast \
		snap-core snap-server transformers-base \
		unordered-containers xmlhtml

.include "${.CURDIR}/../../lang/ghc/bsd.cabal.mk"
.include <bsd.port.mk>
