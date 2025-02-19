## 1.1.11.15 (2023-07-20)

Add an upstream_repository field to METADATA.toml (#10487)

Closes: #10478

## 1.1.11.14 (2023-05-10)

Add `partial_stub` metadata field (#10157)

## 1.1.11.13 (2023-03-27)

Add defaults for third-party stubs E-H (#9954)

## 1.1.11.12 (2023-02-21)

Stubtest settings: change `ignore_missing_stub` default to `false` (#9779)

If you're reading about this commit from an autogenerated changelog entry, this should have no user-visible impact on how the stubs are interpreted by a type checker; it's just an internal change to how typeshed's tests work.

## 1.1.11.11 (2023-01-18)

Replace `Any` with `Incomplete` in many places (#9558)

## 1.1.11.10 (2022-11-23)

`__unicode__` always returns `str` (#9248)

Mark first argument of `__[get|set|del]attr__` as `str` (#9245)

## 1.1.11.1 (2022-11-09)

Annotate known magic-method return types (#9131)

## 1.1.11 (2022-09-27)

Bump mypy to 0.981 (#8796)

## 1.1.10 (2022-08-18)

Support extras in stubtest_third_party.py (#8467)

## 1.1.9 (2022-07-19)

Third-party stubs: enforce CamelCase for type alias names (#8256)

Co-authored-by: Jelle Zijlstra <jelle.zijlstra@gmail.com>

## 1.1.8 (2022-07-11)

Remove Python 3.6 branches from typeshed (#8269)

## 1.1.7 (2022-04-16)

Use `TypeAlias` where possible for type aliases (#7630)

## 1.1.6 (2022-04-05)

Mark many attributes as read-only properties (#7591)

## 1.1.4 (2021-12-28)

Use PEP 585 syntax wherever possible (#6717)

## 1.1.3 (2021-12-17)

Use stubtest 0.920 (#6589)

Co-authored-by: Alex Waygood <Alex.Waygood@Gmail.com>
Co-authored-by: Jelle Zijlstra <jelle.zijlstra@gmail.com>
Co-authored-by: Sebastian Rittau <srittau@rittau.biz>
Co-authored-by: Akuli <akuviljanen17@gmail.com>

## 1.1.2 (2021-10-12)

Add star to all non-0.1 versions (#6146)

