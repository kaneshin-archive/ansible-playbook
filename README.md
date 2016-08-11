# playbook for Ansible

- ansible 2.0.1.0+

## Support

- Debian 8

## Play!!

```shell
ansible-playbook -i "[your-ip]," --user=`whoami` --private-key=~/.ssh/id_rsa playbook.yml
```

### localhost

```shell
ansible-playbook localhost.yml
```

## References

[Best Practices](http://docs.ansible.com/ansible/playbooks_best_practices.html#best-practices)

## License

[The MIT License (MIT)](http://kaneshin.mit-license.org/)

## Author

[Shintaro Kaneko](https://github.com/kaneshin) <kaneshin0120@gmail.com>

