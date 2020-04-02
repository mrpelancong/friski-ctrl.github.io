<template>
  <f7-page name="home">
    <!-- Top Navbar -->
    <f7-navbar :sliding="false" >
      <f7-nav-left>
        <f7-link icon-md="material:vpn_lock" panel-open="left"></f7-link>
      </f7-nav-left>
      <f7-nav-title sliding>Corona Palembang</f7-nav-title>
    </f7-navbar>
    <!-- Toolbar-->
    <f7-toolbar bottom>
      <f7-link>Left Link</f7-link>
      <f7-link>Right Link</f7-link>
    </f7-toolbar>
    <!-- Page content-->
    <f7-block>
      <f7-row>
        <f7-col>
          <f7-card
            title="Card header"
            content="Card with header and footer. Card headers are used to display card titles and footers for additional information or just for custom actions."
            footer="Card footer"
          ></f7-card>
        </f7-col>
        <f7-col>
          <f7-card
            content="Another card. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse feugiat sem est, non tincidunt ligula volutpat sit amet. Mauris aliquet magna justo. "
          ></f7-card>
        </f7-col>
      </f7-row>
    </f7-block>

  </f7-page>
</template>