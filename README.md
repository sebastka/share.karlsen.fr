# share.karlsen.fr

Simple platform for sharing files though a web interface.

## How to

1. Set up public_html as Apache's `www_root`
2. Use `./mkuser john` in order to create new users
3. To share FILE to a user, run: `ln -s ../../../files/FILE public_html/users/USER/`
