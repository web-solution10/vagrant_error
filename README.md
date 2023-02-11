> **This command:**

```
vagrant box add ubuntu/focal64
```

> **always cause this error:**

```
Traceback (most recent call last):
        2: from C:/HashiCorp/Vagrant/embedded/gems/2.3.4/gems/vagrant-2.3.4/bin/vagrant:111:in `<main>'
        1: from C:/HashiCorp/Vagrant/embedded/mingw32/lib/ruby/2.7.0/rubygems/core_ext/kernel_require.rb:83:in `require'
C:/HashiCorp/Vagrant/embedded/mingw32/lib/ruby/2.7.0/rubygems/core_ext/kernel_require.rb:83:in `require': cannot load such file -- vagrant (LoadError)
        32: from C:/HashiCorp/Vagrant/embedded/gems/2.3.4/gems/vagrant-2.3.4/bin/vagrant:111:in `<main>'
        31: from C:/HashiCorp/Vagrant/embedded/mingw32/lib/ruby/2.7.0/rubygems/core_ext/kernel_require.rb:147:in `require'
        30: from C:/HashiCorp/Vagrant/embedded/mingw32/lib/ruby/2.7.0/rubygems/core_ext/kernel_require.rb:158:in `rescue in require'
        29: from C:/HashiCorp/Vagrant/embedded/mingw32/lib/ruby/2.7.0/rubygems/core_ext/kernel_require.rb:158:in `require'
        28: from C:/HashiCorp/Vagrant/embedded/gems/2.3.4/gems/vagrant-2.3.4/lib/vagrant.rb:352:in `<top (required)>'
        27: from C:/HashiCorp/Vagrant/embedded/gems/2.3.4/gems/vagrant-2.3.4/lib/vagrant.rb:352:in `each'
        26: from C:/HashiCorp/Vagrant/embedded/gems/2.3.4/gems/vagrant-2.3.4/lib/vagrant.rb:360:in `block in <top (required)>'
        25: from C:/HashiCorp/Vagrant/embedded/gems/2.3.4/gems/vagrant-2.3.4/lib/vagrant.rb:360:in `each'
        24: from C:/HashiCorp/Vagrant/embedded/gems/2.3.4/gems/vagrant-2.3.4/lib/vagrant.rb:343:in `block in <top (required)>'
        23: from C:/HashiCorp/Vagrant/embedded/gems/2.3.4/gems/vagrant-2.3.4/lib/vagrant.rb:343:in `load'
        22: from C:/HashiCorp/Vagrant/embedded/gems/2.3.4/gems/vagrant-2.3.4/plugins/commands/cloud/plugin.rb:2:in `<top (required)>'
        21: from C:/HashiCorp/Vagrant/embedded/mingw32/lib/ruby/2.7.0/rubygems/core_ext/kernel_require.rb:83:in `require'
        20: from C:/HashiCorp/Vagrant/embedded/mingw32/lib/ruby/2.7.0/rubygems/core_ext/kernel_require.rb:83:in `require'
        19: from C:/HashiCorp/Vagrant/embedded/gems/2.3.4/gems/vagrant_cloud-3.0.5/lib/vagrant_cloud.rb:1:in `<top (required)>'
        18: from C:/HashiCorp/Vagrant/embedded/mingw32/lib/ruby/2.7.0/rubygems/core_ext/kernel_require.rb:83:in `require'
        17: from C:/HashiCorp/Vagrant/embedded/mingw32/lib/ruby/2.7.0/rubygems/core_ext/kernel_require.rb:83:in `require'
        16: from C:/HashiCorp/Vagrant/embedded/gems/2.3.4/gems/excon-0.94.0/lib/excon.rb:38:in `<top (required)>'
        15: from C:/HashiCorp/Vagrant/embedded/mingw32/lib/ruby/2.7.0/rubygems/core_ext/kernel_require.rb:83:in `require'
        14: from C:/HashiCorp/Vagrant/embedded/mingw32/lib/ruby/2.7.0/rubygems/core_ext/kernel_require.rb:83:in `require'
        13: from C:/HashiCorp/Vagrant/embedded/gems/2.3.4/gems/excon-0.94.0/lib/excon/socket.rb:2:in `<top (required)>'
        12: from C:/HashiCorp/Vagrant/embedded/mingw32/lib/ruby/2.7.0/rubygems/core_ext/kernel_require.rb:83:in `require'
        11: from C:/HashiCorp/Vagrant/embedded/mingw32/lib/ruby/2.7.0/rubygems/core_ext/kernel_require.rb:83:in `require'
        10: from C:/HashiCorp/Vagrant/embedded/mingw32/lib/ruby/2.7.0/resolv.rb:38:in `<top (required)>'
         9: from C:/HashiCorp/Vagrant/embedded/mingw32/lib/ruby/2.7.0/resolv.rb:168:in `<class:Resolv>'
         8: from C:/HashiCorp/Vagrant/embedded/mingw32/lib/ruby/2.7.0/resolv.rb:171:in `<class:Hosts>'
         7: from C:/HashiCorp/Vagrant/embedded/mingw32/lib/ruby/2.7.0/rubygems/core_ext/kernel_require.rb:83:in `require'
         6: from C:/HashiCorp/Vagrant/embedded/mingw32/lib/ruby/2.7.0/rubygems/core_ext/kernel_require.rb:83:in `require'
         5: from C:/HashiCorp/Vagrant/embedded/mingw32/lib/ruby/2.7.0/win32/resolv.rb:7:in `<top (required)>'
         4: from C:/HashiCorp/Vagrant/embedded/mingw32/lib/ruby/2.7.0/rubygems/core_ext/kernel_require.rb:83:in `require'
         3: from C:/HashiCorp/Vagrant/embedded/mingw32/lib/ruby/2.7.0/rubygems/core_ext/kernel_require.rb:83:in `require'
         2: from C:/HashiCorp/Vagrant/embedded/mingw32/lib/ruby/2.7.0/win32/registry.rb:4:in `<top (required)>'
         1: from C:/HashiCorp/Vagrant/embedded/mingw32/lib/ruby/2.7.0/win32/registry.rb:72:in `<module:Win32>'
C:/HashiCorp/Vagrant/embedded/mingw32/lib/ruby/2.7.0/win32/registry.rb:72:in `find': unknown encoding name - CP720 (ArgumentError)
```
