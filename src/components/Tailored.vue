<template>
  <div class="container">
    <div class="row align-items-center">
      <div class="col-lg-6">
        <img src="/images/cinta_800.jpg" alt />
      </div>
      <div class="col-lg-5 offset-lg-1">
        <h2>{{ $t('tailored') }}.</h2>
        <p>{{ $t('tailored_explained') }}.</p>
        <div class="space" data-m-y="50px"></div>
        <div class="icon-box icon-box-left">
          <div class="icon-box-icon">
            <i class="far fa-square"></i>
          </div>
          <div class="icon-box-title">
            <h6>{{ $t('planed_wood_4_faces') }}</h6>
          </div>
          <div class="icon-box-content">
            <p>{{ $t('any_size_any_type') }}.</p>
          </div>
        </div>
        <div class="icon-box icon-box-left">
          <div class="icon-box-icon">
            <i class="fab fa-gg"></i>
          </div>
          <div class="icon-box-title">
            <h6>{{ $t('moulding_gap') }}</h6>
          </div>
          <div class="icon-box-content">
            <p>{{ $t('moulding_gap_explained') }}.</p>
          </div>
        </div>
        <div class="icon-box icon-box-left">
          <div class="icon-box-icon">
            <i class="fas fa-eraser"></i>
          </div>
          <div class="icon-box-title">
            <h6>{{ $t('shaving') }}</h6>
          </div>
          <div class="icon-box-content">
            <p>{{ $t('shaving_explained') }}</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
