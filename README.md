# JavaScript-Learning-Angular
函数声明 是在 JavaScript 准备启动脚本并在其中时创建的。
而函数表达式是在运行至这一行代码时构建该函数的
#函数声明只在它所在的代码块中可见

ngAfterViewInit() {
  var s = document.createElement("script");
  s.type = "text/javascript";
  s.src = "http://somedomain.com/somescript";
  this.elementRef.nativeElement.appendChild(s);
}
