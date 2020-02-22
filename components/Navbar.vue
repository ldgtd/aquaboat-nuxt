<template>
  <div class="navbar-wrapper navbar-wrapper--desktop">
    <header class="navbar">
      <div class="navbar__body">
        <div class="container">
          <div class="navbar__start">
            <!-- <a href="tel:<?= $site->phone()->html() ?>" class="btn pdgl0">
              <?= snippet('icon', array('id' => 'phone', 'class' => 'icon--medium mrgr--')) ?>
              <?= t('contact-us') ?>
            </a> -->
          </div>
          <div class="navbar__center">
            <Logo />
          </div>
          <div class="navbar__end">
            <!-- <?php snippet('switcher-languages') ?> -->
          </div>
        </div>
        <div class="container">
          <ul class="nav-primary">
            <!-- <?php foreach($pages->visible() as $item): ?>
              <li>
                <a href="<?= $item->url() ?>" class="<?= r($item->isOpen(), 'is-active') ?>">
                  <?= $item->title()->html() ?>
                </a>
              </li>
            <?php endforeach ?> -->
          </ul>
        </div>
      </div>
    </header>
  </div>
</template>

<script>

import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>
