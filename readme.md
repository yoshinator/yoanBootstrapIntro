# Navbar
 nav.navbar.navbar-expand-sm.bg-dark.navbar-dark.fixed-top
  .container
    a.navbar-brand
    button.navbar-toggler data-toggle="collapse" data-target="#navbarCollapse"
      span.navbar-toggler-icon
    .collpase.navbar-collapse#navbarCollapse"
      ul.navbar-nav.ml-auto
        li.nav-item
          a.nav-link href=home Hoome
        li.nav-item
          a.nav-link href=explore explore


# Home Section

header#home-section
  .dark-overlay
    .home-inner.container
      .row
        .col-lg-8.d-none.d-lg-block
          h1.display-4 PLAY BEER PONG AND <strong>LEARN TO CODE<strong>
          .d-flex
            .p-4.align-self-start
              i.fas.fa-check.fa-2x
            .p-4.align-self-end
          .d-flex
            .p-4.align-self-start
              i.fas.fa-check.fa-2x
            .p-4.align-self-end
          .d-flex
            .p-4.align-self-start
              i.fas.fa-check.fa-2x
            .p-4.align-self-end
        .col-lg-4
          .card.bg-primary.text-center
            h3 sign up
            p fill out to register
            form
              .form-group
                input.form-control.form-control-lg username
              .form-group
                input.form-control.form-control-lg password
              input.btn btn-outline-light.btn-block submit

