# Tavolio Desk releases

Public release repository for the native Windows Tavolio Desk application.

Create this repository as `RestaurantPOS1/desktop-app-releases`, public, with
`main` as its default branch. The private `desktop-app` GitHub Actions workflow
publishes an unsigned `Tavolio-Desk-Windows-x64.exe`, its SHA-256 checksum,
and Velopack update packages per stable three-part `vX.Y.Z` release. This
repository contains no source or credentials.

Customers install the EXE from the Tavolio website. The native app checks the
public release feed, stages a newer update package in the background, and
applies it in place on its next launch. Do not edit or replace a published
release asset; publish a higher version instead.
