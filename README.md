# learn_scss
노마드코더 <CSS Layout 마스터>

## Content
### SCSS
코드의 재활용성 및 가독성을 높여 개발의 효율을 올리기 위한 CSS 전처리기 언어이다.

#### Variables
+ website에서 중요한 color, styles을 저장하고 싶을 때 사용한다.
+ src/scss/_variables.scss(파일명 앞에 _가 있으면 css로 컴파일되지 않는다.(scss만을 위한 파일))

#### Nesting
+ 중첩
+ 코드를 직관적으로 작성 가능하다.

#### Mixins
+ SCSS functionality를 재사용할 수 있게 해준다.
+ src/scss/mixins.scss
+ @mixin (mixins.scss)
+ @include (styles.scss)

#### Extend
+ 다른 코드를 확장(extend) 하거나 코드를 재활용하고 싶을 때 사용한다.
+ page에서 분리해야하는 element들이 많을 때 유용하다.
+ src/scss/_buttons.scss
+ % (_buttons.scss)
+ @extend (styles.scss)

#### Responsive Mixins
+ @content (mixins.scss)
+ include (styles.scss)
