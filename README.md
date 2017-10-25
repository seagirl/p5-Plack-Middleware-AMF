# p5-Plack-Middleware-AMF

Plack::Middleware::AMF - The great new Plack::Middleware::AMF!

## SYNOPSIS

```
use Plack::Builder;

builder {
    enable "AMF", path => qr/^\/amf\/gateway/;
	$app
};
```

## INSTALLATION

To install this module, run the following commands:

```sh
perl Makefile.PL
make
make test
make install
```

## SUPPORT AND DOCUMENTATION

After installing, you can find documentation for this module with the
perldoc command.

```sh
perldoc Plack::Middleware::AMF
```

You can also look for information at:

- RT, CPAN's request tracker
  - [http://rt.cpan.org/NoAuth/Bugs.html?Dist=Plack-Middleware-AMF](http://rt.cpan.org/NoAuth/Bugs.html?Dist=Plack-Middleware-AMF)
- AnnoCPAN, Annotated CPAN documentation
  - [http://annocpan.org/dist/Plack-Middleware-AMF](http://annocpan.org/dist/Plack-Middleware-AMF)
- CPAN Ratings
  - [http://cpanratings.perl.org/d/Plack-Middleware-AMF](http://cpanratings.perl.org/d/Plack-Middleware-AMF)
- Search CPAN
  - [http://search.cpan.org/dist/Plack-Middleware-AMF/](http://search.cpan.org/dist/Plack-Middleware-AMF/)