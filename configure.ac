AC_INIT([example], 0.0)

AC_ARG_WITH(
    [host],
    [AS_HELP_STRING([--with-host=HOST],
        [target host to connect in tests])],
    [host="$withval"],
    [host=localhost]
)

AC_SUBST([HOST], $host)

AC_CONFIG_FILES([tests/example.phpt])
AC_OUTPUT
