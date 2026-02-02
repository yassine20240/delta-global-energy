 
/*--------------------------------------------------------------
# Services Section
--------------------------------------------------------------*/
.services .service-item {
  background-color: var(--surface-color);
  padding: 30px;
  transition: 0.3s;
}

.services .service-item .icon {
  font-size: 36px;
  line-height: 0;
  margin-right: 30px;
  color: #f7f7f7;
}

.services .service-item .title {
  font-weight: 700;
  margin-bottom: 15px;
  font-size: 20px;
}

.services .service-item .title a {
  color: var(--heading-color);
}

.services .service-item .description {
  line-height: 24px;
  font-size: 14px;
  margin: 0;
}

.services .service-item:hover {
  background-color: color-mix(in srgb, var(--surface-color) 90%, white 5%);
}
