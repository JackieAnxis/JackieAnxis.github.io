## Get started

1. git clone

   ```bash
   git clone git@github.com:jiacheng-pan/jiacheng-pan.github.io.git
   ```

2. npm install

   ```bash
   npm install
   ```

3. add themes

   ```bash
   git clone https://github.com/xaoxuu/hexo-theme-resume.git themes/resume
   ```

4. some css changes:

   1. fancybox: `source\css\page.styl`

      ```styl
      fancybox
         display: flex
         border: 1px solid grey
         margin-left: 3%
         border-radius: 4px
      ```

   2. code:
      1. `source\css\_common.styl:`
         ```styl
         code
            color: #848484
            // background-color: #eee
            background-color: $codebg
            border: 1px solid darken($codebg, 10%)
            padding: 3px 4px 1px 4px
            margin: 0 2px
            border-radius: 2px
            word-break: break-all
            white-space: nowrap;
         ```
      2. `source\css\page.styl`:
         ```styl
         a
            word-break: break-all
            color: $color_link
            font-weight: 600
            hoverable_text()
            // i
            //   &.fa-fw:first-child
            //     margin 0
            code
               color: $color_link
         ```
   3. h4: `source\css\page.styl`

      ```styl
      h4
         margin: $h4-margin-top 0 0
         color: $medium
         text-align: left
         font-size: 1.2em
      ```

   4. li: `source\css\page.styl`

      ```styl
      ul, ol
         ...
         li
         text-align: left
      ```

   5. h3: `source\css\page.styl`

      ```styl
      h3
         margin: $h3-margin-top 0 0
         line-height: 1.2
         position: relative
         font-size: 1.6em
      ```

   6. font: `source\css\_settings.styl`

      ```styl
      // font faces
      $body-font = Corbel, Menlo, Monaco, Courier, "Helvetica Neue", Arial, sans-serif
      $logo-font = Corbel, Menlo, Monaco, Courier, "Helvetica Neue", Arial, sans-serif, cursive
      $code-font = Consolas, Menlo, Monaco, courier, monospace, Arial, sans-serif

      // font sizes
      $body-font-size = 1em
      $code-font-size = 0.8em
      ```

   7. div.btns: `source\css\page.styl`
      ```styl
      .content
         ...
         .btns
            text-align: left
      ```
