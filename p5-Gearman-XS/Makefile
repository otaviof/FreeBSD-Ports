# New ports collection makefile for:	p5-Gearman-XS
# Date created:				July 3rd 2009
# Whom:	      				Alex Kapranoff <ka@nadoby.ru>
#
# $FreeBSD: ports/devel/p5-Gearman-XS/Makefile,v 1.5 2010/01/03 19:36:33 linimon Exp $
#

PORTNAME=	Gearman-XS
PORTVERSION=	0.7
CATEGORIES=	devel perl5
MASTER_SITES=	CPAN
PKGNAMEPREFIX=	p5-

MAINTAINER=	otavio.fernandes@locaweb.com.br
COMMENT=	Perl front end for the Gearman C library

LIB_DEPENDS=	gearman.3:${PORTSDIR}/devel/gearmand

CFLAGS+=	-I${LOCALBASE}/include

PERL_CONFIGURE=	yes

INSTALL_TARGET=	pure_install

MAN3=		Gearman::XS.3 Gearman::XS::Client.3 \
		Gearman::XS::Job.3 Gearman::XS::Server.3 \
		Gearman::XS::Task.3 Gearman::XS::Worker.3

.include <bsd.port.mk>
