# Ansible Role: Google Chrome

Install [Google Chrome Browser](https://www.google.com/chrome/browser/desktop/index.html) from Google repository.

## Requirements

- Ansible >= 2.2
- Fedora 25
- sudo

The role may run on other systems, but it is not tested.

## Role Variables

Keep Google Chrome update (present | latest | absent).
```
google_chrome_update: latest
```
Google Chrome channel (google-chrome-stable | google-chrome-beta | google-chrome-unstable).
```
google_chrome_version: google-chrome-stable
```

## Example

```
- hosts: all
  roles:
    - ansible-role-google-chrome
```

## Dependencies

None

## License

MIT

## Author Information

Apostolos Tovletoglou [ansible-role-google-chrome](https://github.com/tovletoglou/ansible-google-chrome)
