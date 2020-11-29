# Wordpress Snippet

**Hide Elementor pro activeate license**

        add_action('admin_head', 'custom_css');

        function custom_css() {
          echo '<style>
            .elementor-message {
              display:none;
            } 
          </style>';
        }
