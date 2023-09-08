这样的话 有一些小的需要布局的 就不需要写class了 我比较懒
# 注册全局（Vite）
  css: {
    preprocessorOptions: {
      // 注册全局scss
      sass: {
        data: `@import "@/assets/style/public.scss";`
      }
    }
  }
