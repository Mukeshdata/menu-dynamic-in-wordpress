# menu-dynamic-in-wordpress
 <?php
                                        $defaults = array(
                                            'theme_location'  => 'header-menu',
                                            'menu'            => 2,
                                            'container'       => false,
                                            'container_class' => '',
                                            'container_id'    => '',
                                            'menu_class'      => 'navbar-nav ml-auto py-4 py-md-0',
                                            'menu_id'         => '',
                                            'echo'            => true,
                                            'fallback_cb'     => 'wp_page_menu',
                                            'before'          => '',
                                            'after'           => '',
                                            'link_before'     => '',
                                            'link_after'      => '',
                                            'items_wrap'      => '<ul id="%1$s" class="%2$s">%3$s</ul>',
                                            'depth'           => 2,
                                            'walker'          => ''
                                            );
                                        wp_nav_menu( $defaults );
                                    ?>
