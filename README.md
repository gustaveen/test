## Proposed BEM structure

    .btn
        &--filled
        &--theme
        &--filter

    .site

    .header-main
        &__content
        &__branding
            &__logo
            &__logo-text
        &__menu | navbar

    .navbar
        &__container
            &__item | &--search | &--title
                &__link | &--current | &--inverted
    main

    hero
        &__content
            &__text

    .feed
        &__filter
            &__filter-label
            &__filter-select
        &__title
        &__item
            &__item-category
            &__item-date
            &__item-title
            &__preamble
            &__item-image
        &__footer
            &__read-more | .btn

    .blurb
        &__content | &--left | &--right
            &__tag
            &__title
            &__preamble
            &__description
            &__btn | .btn
            &__image

    article.infobox
        &__item | &--{modifier}
        &__title
        &__description
        &__btn | .btn

    footer.footer
        .navbar
            .navbar__item
                .navbar__link
        &__signature
            &__text
        .social
            &__link

    .header-page-menu
        &__summary
            &__image
            &__title
            &__description
        &__menu | .navbar--vertical | .navbar--2-column
            .navbar__item
                .navbar__link

    .header-page
        &__tag
        &__title

    .page-content
        .wysiwyg
            p
            a
            ul
                li

    .menu-collection
        &__item
            &__link

    .page-content-contact || .page-content
        &__info | .wysiwyg
        &__image

    .page-content-resource || .page-content
        &__info | .wysiwyg
        &__item
            &__title
            &__image
            &__description

    .login
        &__item
            &__input
            &__checkbox
            &__btn | .btn

    .contact-form
        &__label
        &__input
        &__select
        &__submit | .btn .btn--filled


    .page-content
        .btn | .btn--filled | .btn--filter | .btn--current
        article.post
            &__date
            &__title
            &__content | .wysiwyg
            &__footer
                &__posted
                &__tags

    .pagination
        &__next
        &__previous
        &__current
        &__page-number




### Media Queries

    /* Media querys used, only for quick copy paste stub */
    @media @media--s {

    }

    @media @media--m {

    }

    @media @media--l {

    }

    @media @media--xl {

    }
