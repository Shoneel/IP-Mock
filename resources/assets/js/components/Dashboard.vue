<template>
    <div class="container">
        <div class="row">
          <div class="col-md-3 col-sm-6 col-12 mt-3">
            <div class="info-box bg-gradient-info">
              <span class="info-box-icon"><i class="far fa-bookmark"></i></span>

              <div class="info-box-content">
                <span class="info-box-text">Today Present</span>
                <span class="info-box-number">12/60</span>

                <div class="progress">
                  <div class="progress-bar" style="width: 30%"></div>
                </div>
                <span class="progress-description">
                  
                </span>
              </div>
              <!-- /.info-box-content -->
            </div>
            <!-- /.info-box -->
          </div>
          <!-- /.col -->
          <div class="col-md-3 col-sm-6 col-12 mt-3">
            <div class="info-box bg-gradient-success">
              <span class="info-box-icon"><i class="far fa-thumbs-up"></i></span>

              <div class="info-box-content">
                <span class="info-box-text">Planned Leaves</span>
                <span class="info-box-number">8 Today</span>

                <div class="progress">
                  <div class="progress-bar" style="width: 70%"></div>
                </div>
                <span class="progress-description">

                </span>
              </div>
              <!-- /.info-box-content -->
            </div>
            <!-- /.info-box -->
          </div>
          <!-- /.col -->
          <div class="col-md-3 col-sm-6 col-12 mt-3">
            <div class="info-box bg-gradient-warning ">
              <span class="info-box-icon"><i class="far fa-calendar-alt"></i></span>

              <div class="info-box-content">
                <span class="info-box-text">Unplanned Leaves </span>
                <span class="info-box-number"> 0 Today</span>

                <div class="progress">
                  <div class="progress-bar" style="width: 0%"></div>
                </div>
                <span class="progress-description">

                </span>
              </div>
              <!-- /.info-box-content -->
            </div>
            <!-- /.info-box -->
          </div>
          <!-- /.col -->
          <div class="col-md-3 col-sm-6 col-12 mt-3">
            <div class="info-box bg-gradient-danger">
              <span class="info-box-icon"><i class="fas fa-comments"></i></span>

              <div class="info-box-content">
                <span class="info-box-text">Pending Requets </span>
                <span class="info-box-number">41</span>

                <div class="progress">
                  <div class="progress-bar" style="width: 70%"></div>
                </div>
                <span class="progress-description">
                </span>
              </div>
              <!-- /.info-box-content -->
            </div>
            <!-- /.info-box -->
          </div>
          <!-- /.col -->
        </div>
    </div>
</template>

<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
