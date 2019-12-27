
## Default Variables

### onepassword_started

Restart app if already running

#### Default value

```yaml
onepassword_started: false
```

### onepassword_user

User to run user-specific commands

#### Default value

```yaml
onepassword_user | default(homebrew_user) | default(ansible_user_id)
```
## Dependencies

None

## License

Apache-2.0

## Author

Thomas Boerger
