# Sublime Text 3

## 安装插件

    import urllib.request,os,hashlib; h = '2915d1851351e5ee549c20394736b442' + '8bc59f460fa1548d1514676163dafc88'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)

## 相关文章
https://packagecontrol.io/installation
https://www.zhihu.com/question/24736400
http://www.oschina.net/translate/20-powerful-sublimetext-plugins
http://bubkoo.com/2014/01/04/sublime-text-3-plugins/
http://www.jianshu.com/p/3cb5c6f2421c
http://www.dbpoo.com/sublime-text3-install/
